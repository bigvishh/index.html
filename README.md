ArcStream — USDC Streaming Payroll on Arc Testnet
A fully on-chain USDC payroll dApp built on Arc Testnet. Employers deposit USDC, add employees with monthly salaries, and earnings stream in real time — second by second. Employees can withdraw their earned USDC anytime.
Live Demo · View on Arc Explorer
What It Does
Employer deposits USDC into the payroll contract
Employer adds employees with monthly salary amounts
Earnings stream continuously — calculated per second on-chain
Employees see live earnings updating every 3 seconds
Employees withdraw their earned USDC anytime with one click
Live stream dashboard shows all active employee streams
Every transaction links to the Arc block explorer
Smart Contract
Deployed on Arc Testnet at:
Code
Solidity
USDC on Arc
Arc uses USDC as its native gas token at:
Code
This makes ArcStream uniquely native to Arc — payroll, gas, and settlement all in USDC. No ETH, no wrapping, no swapping.
Network Details
Parameter
Value
Network
Arc Testnet
Chain ID
5042002
RPC
https://rpc.testnet.arc.network
Gas token
USDC
Explorer
testnet.arcscan.app
How to Use
As Employer
Connect wallet (Rabby or MetaMask) on Arc Testnet
Get testnet USDC from faucet.circle.com
Go to Employer tab → Deposit USDC
Add employees with wallet address and monthly salary
Earnings start streaming immediately
As Employee
Connect wallet on Arc Testnet
Go to Employee tab
Watch earnings update live every 3 seconds
Hit Withdraw anytime to receive your USDC
Run Locally
Bash
Wallet connections require HTTPS — test via GitHub Pages, not a local file.
Built With
Vanilla HTML, CSS, JavaScript
ethers.js v6
Remix IDE — contract deployment
Arc Testnet — EVM L1 with USDC as native gas token
Google Fonts — Space Mono + Syne
Made by @bigvishh · @Arcstream on X
