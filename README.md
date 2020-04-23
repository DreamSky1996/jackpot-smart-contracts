# Jack's Pot Smart Contract

Jack’s Pot is a no-loss lottery game built on Wanchain which draws from the design of the Ethereum based PoolTogether game while introducing novel game mechanics. 

To play the game, participants deposit WAN while also guessing a number between 1 and 4 inclusive. 

Participants' WAN deposits are delegated to POS verification nodes, and the accrued consensus rewards are pooled into a prize pot. 

Every Friday a winning number is selected at random using Wanchain’s true random number generation, and the reward will be awarded proportionally to participants who guessed the winning number. 

If there is no winner, the prize pot will automatically accumulate to the next cycle.

# Code Compile

```
yarn
./node_modules/.bin/truffle compile
```

# Run Code Test

You should first start a rpc server at http://localhost:7545

Then run:

```
yarn test
```

# Run Code Coverage Analysis

```
yarn coverage
```

Then you can find a HTML-UI in coverage/index.html 

