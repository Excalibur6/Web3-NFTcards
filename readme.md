# Avax Gods - Online Multiplayer Web3 NFT Card Game

![Gameplay](https://i.ibb.co/4P2C08x/image.png)


## Instructions on Setting Up the Web3 Part of the Project

### 0. Navigate to the Web3 Directory
```sh
cd web3

npx hardhat

npm install @openzeppelin/contracts dotenv @nomiclabs/hardhat-ethers
npm install --save-dev hardhat@^2.12.0 @nomicfoundation/hardhat-toolbox@^2.0.0
```

3. Install Metamask Smart Wallet Alternative for Avalanche dApps
Open the Core extension.
Click the hamburger menu on the top left.
Go to Advanced.
Turn on the Testnet Mode.
4. Fund Your Wallet
Use the Avax Faucet to fund your wallet.

5. Create a .env File
Specify a PRIVATE_KEY variable in the .env file.

6. Obtain Your Private Key
Open the Core extension.
Click the hamburger menu on the top left.
Go to Security and Privacy.
Click Show Recovery Phrase.
Enter your password and copy the recovery phrase.
Go to wallet.avax.network.
Click Access Wallet.
Choose Mnemonic Key Phrase and paste the copied phrase.
On the sidebar, click Manage Keys -> View C-Chain Private Key.
Copy the private key and paste it in the .env file.
7. Copy hardhat.config.ts File
Copy the hardhat.config.ts file from the GitHub gist provided in the description.

8. Copy deploy.ts Script
Copy the deploy.ts script from the GitHub gist provided in the description.

9. Copy AvaxGods.sol Smart Contract Code
Copy the AvaxGods.sol smart contract code from the GitHub gist provided in the description.
