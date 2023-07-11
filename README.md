# Proveably Random Raffle Contracts

## About

This code is to create a proveably random smart contract lottery.

https://github.com/Cyfrin/foundry-smart-contract-lottery-f23

## What we want it to do?

1. Users can enter by paying for a ticket.
    The ticket fees are going to the winner during the draw.

2. After X period of time, the lottery will automatically draw a winner.
    And this will be done programatically.

3. Using Chainlink VRF & Chainlink Automation.
    Chainlink VRF -> Randomness.
    Chainlink Automation -> Time based trigger.


## Tests!

1. Write some deploy scripts
2. Write our tests
    1. Work on a local chain
    2. Forked Testnet (Didn't set up subscription)
    3. Forked Mainnet (Also not set up)
        
TODO:

1. Integrations Tests
2. Deploy on Sepolia Test Net and Fund Chainlink VRFv2 and Chainlink Automations Subscriptions