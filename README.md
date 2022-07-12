# Lesson 15 in Patrick's course

- Pull over Push -> put the responsability of receiving ETH to the user
- We talk about reentrancy attack

- Get the token ID from event emitted: `const tokenId = mintTxReceipt.events[0].args.tokenId`

- It is recomendable that test have a coverage of at least 90%

- To run a script after you have a local blockchain running: `hh run scripts/mint-and-list-item.js --network localhost`

- 1 day 24 minutes 26 sec -> possible PR
