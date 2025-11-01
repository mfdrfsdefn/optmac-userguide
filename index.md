# OptMachine user guide
Welcome to be the user of this dapp I will show you how to use it step by step


## 0. Requirements
- A Solana wallet (Phantom)
- Small amount of **DEVNET SOL** for fees
- You can click the faucet button to visit solana faucet to 
get some devnet sol 
- SET THE WALLET IN TESTNET MODE
<p align="center">
  <img src="./images/devnet.png" width="500">
</p>
## 1. Connect wallet and get test tokens
- First, click the connect wallet button to connect your wallet to the website
- Then, click the airdrop button to get test tokens. We will provide you 1000 token A and 1000 token B
  
<p align="center">
  <img src="./images/wallet-start.png" width="1000">
</p>

## 2. Create & Mint your first option
- You should create your option before you mint it
- You can set any parameter to your option, but make sure your expiration is set after your time or the option will not be created
- Also, we recommend you to set it in an appropriate size so that you can mint
- You can see the option mint on transaction logs
<p align="center">
  <img src="./images/create-option.png" width="1000">
</p>

-  Copy the option mint and paste it on the option parser, you can see the detail of the option token
  <p align="center">
  <img src="./images/option-parser.png" width="1000">
</p>

- Now you can mint your option 
- As you mint your option your underlying asset will be transfered to the vault if users exercise option the vault will send 
- underlying asset to the exerciser and the creator will receive the quote tokens
  <p align="center">
  <img src="./images/mint-option.png" width="1000">
</p>

-You will find option tokens in your wallet 
  <p align="center">
  <img src="./images/option-token.png" width="1000">
</p>

## 3. Exercise option
- First of all, check the option token in our option parser
- Then, paste the option token mint into exercise option and choose the amount of options you'd like to exercise
- After you exercise the option token will be burned and underlying of the option will be sent to you from the vault
- Your quote token will be transfered to the creator of the option 
  <p align="center">
  <img src="./images/exercise.png" width="1000">
</p>

## 4. Reclaim assets
- After the option expires creator of the option can reclaim the collateral in the vault
    <p align="center">
  <img src="./images/reclaim.png" width="1000">
</p>
