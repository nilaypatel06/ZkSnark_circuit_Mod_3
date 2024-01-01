## Description

This project illustrates the steps involved in crafting a custom circuit using zkSNARK (Zero-Knowledge Succinct Non-Interactive Argument of Knowledge). It encompasses setting up essential dependencies, generating a circuit using Circom, and deploying the resultant circuit to the Mumbai network.

### Installation

1. Clone the repository: `https://github.com/nilaypatel06/ZkSnark_circuit_Mod_3.git`
2. Install the required dependencies: `npm install`

### Executing Program

Follow the steps below to execute the custom circuit creation:

1. Make sure you has some test MATIC in your address.
2. Create a custom circuit using this command: `npx hardhat circom`
3. Deploy the circuit to the Mumbai network using this command: `npx hardhat run scripts/deploy.ts --network mumbai`

## Authors

- Neel Bareja
