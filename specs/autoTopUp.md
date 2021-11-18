## Auto Top Up

### Description

Please describe the general job here that Gelato should perform giving as much detail as is needed to understand.

a) the network your task should be running on (e.g. Ethereum, Polygon, Fantom, Arbitrum, BSC or Avalanche)

=> Ethereum

b) the smart contract address to execute a function on

=> Not yet deployed, but basically this [AutoTopUp](https://github.com/gelatodigital/auto-top-up). Needs to be updated though to make it work with Ops. 

c) which function to execute on that smart contract

=> Paying out an ETH amount to a specific address

d) when to execute that function (i.e. descripe the condition)

=> If the ETH balance of the pre-defined address drops below a certain treshold

e) what data to use to execute it. Please link any relevant smart contracts.

=> Address of recepient, amount and threshold. The list of all the addresses that we should check is [here](https://thegraph.com/hosted-service/subgraph/azf20/buidl-guidl-streams?version=pending). The threshold should be set globally for all these addreses.

### Difficulty

Low / moderate / high

=> moderate

### Task payment

How will you pay for your transactions? Do you want to just top up your e.g. ETH Balance on Gelato to pay for tranasctions, or is there a payment model already encoded into the function that will pay Gelato Executors to execute that function? 

=> function will pay for itself by taking a cut in the ETH

### Rewards

Incentivizing someone to write the smart contracts necessary to automate your task is a good idea to speed things up! Please note how much you would you willing to donate to the developer.

=> 1 ETH
### Other

This template is the minimum for inclusion. Free to add any other information you feel is valuable, including where to go for support.