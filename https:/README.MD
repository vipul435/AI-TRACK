# InteractionLogger Smart Contract

This repository contains the **InteractionLogger** smart contract, written in Solidity. This contract allows users to log interactions with timestamps and retrieve logged data.

## Features
- Stores interaction timestamps on the blockchain.
- Provides functions to log an interaction and retrieve stored timestamps.
- Retrieves total interactions count.
- No constructor or input fields required during deployment.

## Smart Contract Address
Deployed on **Edu Chain** at:
```
0x7980120991cB822d6C9a12FefcDCfD77aD868D49
```

## Functions
- **logInteraction()** → Logs an interaction by storing the current timestamp.
- **getInteraction(uint256 index)** → Retrieves the timestamp of a specific interaction.
- **getTotalInteractions()** → Returns the total number of logged interactions.

## How to Use
1. Interact with the contract via blockchain explorers or smart contract interfaces.
2. Call `logInteraction()` to record an interaction.
3. Use `getInteraction(index)` to retrieve timestamps of past interactions.
4. Use `getTotalInteractions()` to get the count of logged interactions.

## License
This project is open-source and free to use.
