### Aptos Connect: MetaMask Snap for Aptos Blockchain Interaction

*Aptos Connect* is a MetaMask Snap that enables users to seamlessly interact with the Aptos blockchain directly from the MetaMask interface. This Snap provides various functionalities to support Aptos account management, message signing, transaction processing, and data handling.

#### Key Features
- *Account Management:* Generate Aptos accounts, view public/private keys, and retrieve account addresses.
- *Transaction Signing:* Sign and send transactions on the Aptos blockchain, including funding accounts and coin transfers.
- *Message Signing:* Sign messages directly through MetaMask.
- *Data Persistence:* Store and retrieve data across sessions securely.
- *RPC Interaction:* Execute RPC requests to Aptos nodes for activities like checking account balances and transaction histories.

#### Live Demo
- [Example Website](https://wallet-aptos.netlify.app/)
- [Demo Video](https://drive.google.com/file/d/1udzGcTMaYwhap0sOGQkJhpG82HjDEsUZ/view?usp=sharing)


#### RPC Methods
- *getAccountAddress:* Retrieve the Aptos account address for a specified derivation path.
- *getPublicKey:* Obtain the public key for the given derivation path.
- *getPrivateKey:* Access the private key (sensitive).
- *createNewAccount:* Generate a new Aptos account.
- *signMessage:* Sign messages using the private key.
- *sign&sendTxn:* Sign and send transactions on Aptos.
- *setData:* Save data in MetaMask’s encrypted storage.
- *getData:* Retrieve stored data.
- *clearData:* Clear all saved data.

Check the documentation for additional RPC methods and usage details.

#### Development
To set up the project locally, clone the repository and install dependencies using Yarn:
git clone https://github.com/Shash-Projects/metamask-snap.git
yarn install
yarn start


##### Frontend Development
cd packages/site
yarn install


##### Snap Development
cd packages/snap
yarn install


#### Snap Availability
- *Production Snap ID:* npm:aptos-connect
- *Local Snap ID:* local:http://localhost:8080

#### License
This project is dual-licensed under the Apache 2.0 License and MIT License.