# SecretAlice
Application idea - Encrypted group messaging
> See this idea：https://github.com/enigmampc/SecretNetwork/issues/91

## Original description：
Encrypted group chat is created based on a secret contract, where messages coming from group members are stored in the secret contract state of Enigma blockchain. Using the concept of encrypted outputs, participants of the chat can access messages.

This application requires an admin (Alice) and other users (Bob and Charlie), who participate in the encrypted messaging

Alice (admin) creates a secret group chat room by deploying the secret contract
Alice adds Bob and Charlie to the chat - there should be a function for access mgmt, where Alice can add Bob and Charlie's public keys - messages would be encrypted in a way such that Alice and Bob and Charlie are able to read
Alice, Bob or Charlier can send messages to the secret contract, each message updates the contract state
Alice, Bob and Charlie should be able to see the msg history through a GUI
Questions:

Would it be possible to encrypt the output such that it can be decrypted by Alice, Bob and Charlie? One option is to encrypt the message n times, where n=3 in this case. Not elegant but would work
Would each chat need to be deployed as a new contract? If so is it going to be expensive for the users (lower priority)

------

## Specific design


### API list
> * api1
> * api2


### TODO
- [ ] fun1
- [x] fun2


------

Learn about scrt:

https://scrt.network/developers

https://build.scrt.network/dev/secret-contracts.html
