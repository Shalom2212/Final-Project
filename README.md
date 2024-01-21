## Getting Started

First, install required libraries:

```bash
npm install
```

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### functionalities of smart contract
smart contract contain mainly a review function where a user can add a new review or update already exisiting review with transcation, where using frontend we connect to smart contract using program_id and send user data to contract and store it in devnet, and also retrive data from smart contract and display it on frontend page.

### guide to deploy and interact
To deploy a smart contract we use solana playground which make deployment process much easier, where first you need a wallet and with some SOL here we use devnet sol, and deploy it in devnet.
In order to interact with smart contract we need program_id and solana package for javascript which help to connect to smart contract and invoke all the functionalities of smart contract.
