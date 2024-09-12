# 📝 Assignment for Week 2

## DIY Smart Contract: **Deadman's switch**

A well-known problem for cryptocurrency holders is that all funds are lost if the owner is incapacitated and has not shared their private key with anyone else. For this week's submission, you are expected to write a smart contract that will send all of its balance to a pre-set address if the owner of that contract has not called a `still_alive` function on the contract in the last 10 blocks.

**Before starting this assignment:**
Please make sure you complete the first 3 modules of the CryptoZombies smart contract course:
1. [Making the Zombie Factory](https://cryptozombies.io/en/lesson/1/chapter/1)
2. [Zombies Attack Their Victims](https://cryptozombies.io/en/lesson/2/chapter/1)
3. [Advanced Solidity Concepts](https://cryptozombies.io/en/lesson/3/chapter/1)

These modules will provide you with the necessary foundation to complete this assignment.

**Exercise:**

1. Design, write, and deploy a deadman's switch contract to Goerli or Sepolia testnet.

**Deadline: 26th September 2024 (Thursday) - 2 weeks from now**

### Submission Guidelines

1. Fork this repository
2. Clone your forked repository to your local machine
3. Create a new branch for your changes: `git checkout -b <your_name>_solution_week_2`
4. Implement the Deadman's Switch contract in `DeadmansSwitch.sol`
5. Commit your changes and push to your forked repository
6. Create a pull request to the original repository

### Resources

- [Remix IDE](https://remix.ethereum.org/)
- [Solidity Documentation](https://docs.soliditylang.org/)
- [OpenZeppelin Contracts](https://docs.openzeppelin.com/contracts/)

#### Video Tutorials
- [Introduction to Remix IDE](https://www.youtube.com/watch?v=JWJWT9cwFbo)
- [How to Compile and Deploy Smart Contracts using Remix](https://www.youtube.com/watch?v=bZKVfXmzRDw)
- [Interacting with Smart Contracts in Remix](https://www.youtube.com/watch?v=OZVBfXb2Yfc&ab_channel=EatTheBlocks)

### How to Compile and Deploy using Remix IDE

1. Open Remix IDE in your browser
2. Create a new file called `DeadmansSwitch.sol` and paste your contract code
3. Compile the contract using the Solidity Compiler tab
4. Switch to the Deploy & Run Transactions tab
5. Select the appropriate environment (Injected Web3 for MetaMask)
6. Deploy the contract with the required constructor parameters
7. After deployment, copy the contract address

### What to Submit

1. The address of your deployed contract on Goerli or Sepolia testnet
   Example: `0x1234567890123456789012345678901234567890`
2. Link to your GitHub Pull Request with the implemented contract

Head over to the Coursework link: https://forms.gle/qWAdJtf91Zs3RgGx9 to submit your work.

Inform your UniDAO lead once the submission has been made.

Feel free to ask any sort of doubts on Discord.
