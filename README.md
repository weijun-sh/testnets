# OKExChain Testnets

This repo collects the genesis and configuration files for the various OKChain
testnets. It exists so the [OKExChain repo](https://github.com/okex/okexchain)
does not get bogged down with large genesis files and status updates.

## Getting Started

To get started with the latest testnet, see the
[docs](https://okexchain-docs.readthedocs.io/en/latest/getting-start/join-okexchain-testnet.html).

## Testnet Status
Source Code: [latest released version](https://github.com/okex/okexchain/releases/tag/v0.16.6.2)

⚠️ Latest testnet: [okexchain v0.16.6.2](https://github.com/okex/okexchain/releases/tag/v0.16.6.2) ⚠️
* *Feb 19, 2021 16:19 UTC* - okexchain-v0.16.6.2

Build v0.16.6.2 okexchaind 
```
make GenesisHeight=914809 install
```

Download the [genesis file](https://raw.githubusercontent.com/okex/testnets/master/v0.16.6/genesis.json)

```bash
$ shasum -a 256 genesis.json
844fe86ae829d53ca7028b892086530f77169b5f83bcd87827389da8d8dfbe89  genesis.json
```

Seed nodes:
```
b7c6bdfe0c3a6c1c68d6d6849f1b60f566e189dd@3.13.150.20:36656
d7eec05e6449945c8e0fd080d58977d671eae588@35.176.111.229:36656
223b5b41d1dba9057401def49b456630e1ab2599@18.162.106.25:36656
```
