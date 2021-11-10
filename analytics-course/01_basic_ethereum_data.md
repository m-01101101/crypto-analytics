# # Basic call and event data on Ethereum

[Lecture slides](https://docs.google.com/presentation/d/1I6vDOS52uMCmWg3KIbuKYe8lK-8_ol9bEksIUEHNNLI/edit#slide=id.p)

> Ethereum is a distributed network of computers running software (known as nodes) that can verify blocks and transaction data. You need an application, known as a client, on your computer to "run" a node. [ref](https://ethereum.org/en/developers/docs/nodes-and-clients/)

There are typically three layers of abstraction when interacting with raw Ethereum data;

1. A client
  - an implementation of Ethereum that verifies all transactions in each block, keeping the network secure and the data accurate
  - you are running one of the computers that makes a blockchain possible
2. Node-as-a-Service
  - third parties or a friend can run a node (running a node is non-trivial in a PoW world) They will provide a public API to write and read from the blockchain
  - if you go to MetaMask -> Settings -> Networks -> Mainnet. The `RPC URL` will display the Node-as-a-Service provider
  - Anytime you're connecting your wallet to a DAPP you're doing so using a Node Endpoint-as-a-service
  - If you were running a client locally, you could point your wallet to your local host
3. Data mappers 
  - tools like Dune and Flipside that do all the ETL of reading from a Node Endpoint and provide an interface to query a SQL database
  - [check out the tools section](#analytics-tools)

![eth abstractions](md_refs/eth_abstractions.svg "Source: Mirror's analytics course")
