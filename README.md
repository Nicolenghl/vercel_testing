# GreenDish Web Application

A decentralized web application for connecting eco-conscious restaurants with customers, rewarding sustainable choices with carbon credits.

## Network Requirements

This application is configured to work with the **Axiomesh Gemini** network (Chain ID: 23413). You'll need to:

1. Configure your MetaMask wallet to connect to Axiomesh Gemini
2. Have some AXC tokens for gas fees and transactions

## Axiomesh Gemini Network Details

Use these details to add the Axiomesh Gemini network to your wallet:

- **Network Name**: Axiomesh Gemini
- **Chain ID**: 23413 (0x5b75 in hex)
- **RPC URL**: https://rpc5.gemini.axiomesh.io
- **Currency Symbol**: AXC
- **Block Explorer URL**: https://scan.gemini.axiomesh.io

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the development server: `npm run dev`
4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Connecting Your Wallet

1. Click the "Connect Wallet" button in the application
2. If your wallet is not already on the Axiomesh Gemini network, you'll be prompted to switch networks
3. Once connected, you can access all features of the application

## Smart Contract

The application interacts with a smart contract deployed on the Axiomesh Gemini network. Make sure your contract is deployed at the address specified in `app/contracts/contract.js`.

## Features

### For Restaurants

- Register as a restaurant with sustainability details
- Add and manage sustainable dishes
- View transaction history

### For Customers

- Browse sustainable restaurants
- Purchase dishes and earn carbon credits
- View profile with carbon credit balance

## Deployment

Deploy this application on Vercel by:

1. Push your code to a GitHub repository
2. Connect your repository to Vercel
3. Deploy with default settings

## Troubleshooting

If you encounter connection issues:

1. Ensure your wallet is connected to Axiomesh Gemini network
2. Verify that your contract is deployed to the correct address
3. Check that you have sufficient AXC for transactions
4. See browser console for detailed error messages

## License

This project is licensed under the MIT License.