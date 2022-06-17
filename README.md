# Choco Smart Contracts 

This is the main Olympus smart contract development repository.

## 📜 Contract Addresses

 - For [Theta Mainnet](https://docs.chocofinance.com/resources/mainnet-contracts).
 - For [Theta Testnet](https://docs.chocofinance.com/resources/testnet-contracts).

### Notes for `localhost`
-   The `deployments/localhost` directory is included in the git repository,
    so that the contract addresses remain constant. Otherwise, the frontend's
    `constants.ts` file would need to be updated.
-   Avoid committing changes to the `deployments/localhost` files (unless you
    are sure), as this will alter the state of the hardhat node when deployed
    in tests.
