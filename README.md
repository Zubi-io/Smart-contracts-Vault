# Smart-contracts-developer-tools
The ability to execute smart contracts is the single largest differentiator between Ethereum and Bitcoin. Smart contracts present a vastly different paradigm of programming than the usual CS 101 class will teach. It is essential that you understand the intricacies of smart contracts, and the Solidity programming language.

The developement of any large project requires the use of developer tools to streamline the process. The tools you will learn in this week’s lab find their place in every smart contract developer’s toolkit.

# 1: Introduction to Solidity
cryptozombies.io
Go through the first 3 courses in the awesome Crypto Zombies course.

# 2: Setup your developement environment

### 2a: Compiling your smart contract
Truffle is an easy-to-use tool for building (and testing, more on that in 2c) smart contracts.

If you want advanced control over compiling your contracts, you can use the vanilla Solidity compiler solc.

### 2b: Run a local Ethereum test chain
Obviously, you cannot test your smart contracts by uploading them to mainnet Ethereum and risk (yourself & others) losing real ETH.

Running an Ethereum test chain locally on your machine is the best practice for testing purposes. You can use Ganache for this.

### 2c: Deploying & testing your contract
Truffle’s Pet Shop tutorial will guide you through the development cycle of writing, compiling, deploying, and then testing your smart contracts.

### 3: Fetching data from a smart contract
Along with writing smart contracts, writing programs (running on your local machine) that can interact with your contracts is also important.

A common task in writing frontends or bots is contract event log monitoring. Watching events is a great way to understand the changes happening in a contract, in real time.
