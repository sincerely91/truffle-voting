# Voting example DApp on Truffle Framework.

This is a DApp example on Ethereum local network using Truffle Framework.

We develop a DApp where the users can create proposals and vote them. Of course, they can vote once per proposal with the options in support, against or absence.

# Preconditions

This dapp is based on the official tutorial of Truffle Framework: http://truffleframework.com/tutorials/pet-shop. So, I strongly recommend to read it before.

You need to pay attention to configure and run Ganache (for a local blockchain) and MetaMask (for a client web blockchain).

# Deployment

* git clone https://github.com/blockchaindev91/truffle-voting.git
* cd truffle-voting
* npm install -g truffle
* npm install
* truffle compile
* truffle migrate --reset
* npm run dev

# TODO:

* Init and end dates to proposals.
* Anonymous users.

# Credits:

Developed by blockchaindev91

We are glad to receive any contribution, idea or feedback.