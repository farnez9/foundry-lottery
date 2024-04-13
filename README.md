# Random Raffle Contracts

## About

1. Users can enter by paying for a ticket
    1. The ticket feed are going to go to the winner during the draw
2. After a certain period of time, the lottery will automatically draw a winner
    1. This will be done using Chainlink VRF and Chainlink Automation

## Usage

### Install
```
$ forge install Cyfrin/foundry-devops@0.0.11 --no-commit && forge install smartcontractkit/chainlink-brownie-contracts@0.6.1 --no-commit && forge install foundry-rs/forge-std@v1.5.3 --no-commit && forge install transmissions11/solmate@v6 --no-commit
```

### Build

```shell
$ forge build
```