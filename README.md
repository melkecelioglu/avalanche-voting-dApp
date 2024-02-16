# Avalanche Voting DApp

This Voting DApp is a decentralized application (DApp) built on the Ethereum blockchain for conducting elections. It provides a secure and transparent platform for voters to cast their votes and for candidates to participate in the electoral process.

## Features

- **Candidate Registration**: Election contract allows the owner to add candidates to the ballot.
- **Voting**: Registered voters can securely cast their votes for their preferred candidates.
- **Vote Counting**: Each vote is recorded on the blockchain, ensuring transparency and immutability of the electoral process.
- **Prevention of Double Voting**: Smart contract prevents voters from casting multiple votes.
- **Owner Privileges**: Only the owner of the contract can add candidates, ensuring the integrity of the election.

## Smart Contract

The heart of this project is the Ethereum smart contract written in Solidity. The smart contract defines the structure of candidates and implements functions for candidate registration and voting.

## Technologies Used

- **Solidity**: Smart contract programming language for Ethereum.
- **Web3.js**: JavaScript library for interacting with the Ethereum blockchain.
- **Truffle**: Development framework for Ethereum smart contracts.
- **React**: JavaScript library for building user interfaces.
- **Next.js**: React framework for building server-side rendered applications.
- **Tailwind CSS**: Utility-first CSS framework for styling the frontend.

## Getting Started

To run the project locally:

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Deploy the smart contract to a local Ethereum network using Truffle.
4. Start the frontend application using `npm run dev`.
5. Access the application in your browser at `http://localhost:3000`.

## Contributing

Contributions are welcome! Feel free to open issues for any bugs or feature requests, or submit pull requests with improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.