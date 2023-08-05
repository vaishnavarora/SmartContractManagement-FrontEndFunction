# SmartContractManagement-FrontEndFunction

## Description
The files `Assessment.sol`, and `deploy.js` contain codes to practice interaction with the `Assesment` smart contract through a website.

## NOTE:
`deploy.js` file contains the code of frontend.

## Environment Setting for Executing the above files
Follow the steps below:

1. Download the zip file and then unpack it, or clone this repository.

2. The `Assessment.sol` file in the repository above contains all the files required to communicate with our smart contract.

3. Transfer the contents of `deploy.js` from this repository to the `deploy.js` file in the `scripts` folder.

4. Put the MetaMask Browser Extension in place.

## Starter Next/Hardhat Project

You should perform the following steps to get the code running on your machine after copying GitHub.

1. Type `npm i` in the terminal while still in the project directory.

2. Add two more terminals to your Visual Studio code.

3. Enter `npx hardhat node` in the second terminal.

4. Type `npx hardhat run --network localhost deploy.js` in the third terminal.

5. To launch the frontend, execute `npm run dev` in the original terminal.

The project will then begin to run on your local host, often at `http://localhost:3000/`.

## Setting up the local host network and a dummy account in your Metamask Wallet

We must create a local network with the MetaMask wallet in order to communicate with the smart contract locally.

1. Select the MetaMask extension, then select the network selection button in the top centre of the screen.

1. Select "Add a Network." 2.

Three. Select "Add a Network Manually."

4. Provide the Network with a name (of your wish).

5. Change the New RPC URL to `http://127.0.0.1:8545/`.

6. Change the Chain ID to `31337`.

7. Change the currency sign to `ETH`.

8. After that, change the MetaMask wallet network to the fresh local network.

You must import an account with the account's private key, which can be found in the second terminal where we ran the command `npx hardhat node` in order to set up an account. After pressing enter, you can see that the terminal has numerous account numbers and private key entries. Simply take the relevant private key for any account and import it into your Metamask Wallet.

Enter `http://localhost:3000/` to access the Metamask Wallet and begin interacting with it.

Additionally, the deploy terminal allows you to view all transactional details.

## Authors
Vaishnav Arora

## License
This project is licensed under the MIT License. See the LICENSE file for details.
