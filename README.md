# Crypto Analytics

An overview of tools and data available.

Something missing, incoorect or unclear? Raise an issue, create a Pull Request, let's make this better.

## Understanding Ethereum data

> Knowing how to navigate and understanding what you see on etherscan


| Field  | Description  |
|---|---|
| Hash | Unique ID of the event  |
| From  | Sender address   |
| To  | Receiver address   |
| Nonce  | Counter how many transaction addresses have been sent. It also determines the sequence of transactions   |
| Gas Price  | This is how much ether is being paid per gas unit   |
| Gas  | Amount of gas this event consumes   |

## Data providers

https://twitter.com/visavishesh/status/1458158005388816393?s=20

### Dune

[Dune](https://dune.xyz/home) transforms on-chain data (promdomindantly ETH based) into easy to use SQL tables. Dune also provides a hosted IDE to query and visualise data, as well as creating dashboards.

No API available. You can pay to export to CSV.

### Flipside

[Flipside](https://www.flipsidecrypto.com/) also transforms on-chain into well structured SQL models, with hosted solutions to write and visualise data.

### Messari

[Messari](https://messari.io/) is a research house. They also provide a Python [API](https://github.com/messari/messari-python-api) and an [example notebook](https://github.com/messari/messari-python-api/blob/master/examples/Messari%20API%20Tutorial.ipynb)

### Token Terminal

https://www.tokenterminal.com/

### The Graph

> [The Graph](https://thegraph.com/en/) is a decentralized protocol for indexing and querying data from blockchains, starting with Ethereum. It makes it possible to query data that is difficult to query directly.

🤷‍♂️ Docs: https://thegraph.com/docs/about/introduction

## Glassnode

A [web application](https://studio.glassnode.com/metrics?a=BTC&m=addresses.ActiveCount) for a huge number of metrics and an [API](https://docs.glassnode.com/api/addresses)

## Santiment

Link: https://santiment.net/

## CCXT

Exchange data https://github.com/ccxt/ccxt

> CCXT wraps a bunch of different exchange APIs into a single library interface. 

## Moonstream

https://github.com/bugout-dev/moonstream


## Understanding the data

- https://docs.flipsidecrypto.com/our-data/tutorials/ethereum-tutorials
- https://docs.dune.xyz/data-tables/data-tables
