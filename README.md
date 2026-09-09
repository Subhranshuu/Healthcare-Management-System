# Healthcare Management System

A code repository for a decentralized healthcare management system built using React.js and Ethereum smart contracts. This system allows healthcare providers to securely add and access patient records on the blockchain.

## Features

- **Connect Wallet:** Users can connect their MetaMask wallet to interact with the Ethereum blockchain.
- **Fetch Patient Records:** Fetch and view patient medical records using their unique patient ID.
- **Add Patient Records:** Only authorized users can add records, including diagnosis and treatment details for patients.
- **Authorize Healthcare Providers:** The contract owner can authorize other healthcare providers to access patient records securely.

## Technologies Used

- **Frontend:** React.js
- **Blockchain:** Ethereum (using the [ethers.js](https://docs.ethers.io/) library)
- **Smart Contract:** Written in Solidity
- **Wallet Integration:** MetaMask (or any Web3-compatible wallet)
 
Installation
Prerequisites
Node.js
MetaMask or any Web3-compatible wallet
Steps to Run Locally
Clone the repository:


git clone https://github.com/Subhranshuu/Healthcare-Management-System.git
cd Healthcare-Management-System
Install dependencies:


npm install
Start the development server:



npm start
Open the app in your browser at http://localhost:3000.

Ensure your MetaMask wallet is connected to a test network (e.g., Rinkeby, Goerli) or the Ethereum mainnet, depending on the network your contract is deployed on.

If you want to deploy your contract, you can use Remix or Truffle to deploy the smart contract and update the contractAddress in the code.

Usage
Connect Wallet: When the app is loaded, it will automatically prompt you to connect your wallet (MetaMask or another Web3 provider).
Add Record: As a healthcare provider or contract owner, you can add patient records by entering the patient's ID, diagnosis, and treatment.
Fetch Records: You can fetch a patient's records by entering their ID.
Authorize Providers: Only the contract owner can authorize other healthcare providers to access records. The contract owner can input the provider's Ethereum address to authorize them.
Contract Deployment
Ensure your smart contract is deployed on a public Ethereum network (mainnet/testnet) before using this application. You can deploy the smart contract using tools like Remix or Truffle.

Once deployed, update the contract address in the contractAddress variable inside the Healthcare.js file...

Contributing
Feel free to fork the repository, create a new branch, and submit a pull request for any bug fixes or improvements.

Fork the repository
Create a new branch (git checkout -b feature-branch)
Commit your changes (git commit -am 'Add new feature')
Push to the branch (git push origin feature-branch)
Create a new pull request
License
This project is licensed under the MIT License - see the LICENSE file for details.

Before starting this app, run

npm install
Update the smart contract address and ABI in the Healthcare.js file.

To run the project, go to the terminal and type:


npm start


This `README.md` is now ready for use in your GitHub repository! It provides a comprehensive guide on setting up and using your decentralized healthcare management system.
