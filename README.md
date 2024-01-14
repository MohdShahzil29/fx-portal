# 🌉 ERC721 Goerli to Mumbai Bridge with fxPortal 🚀
Embark on a seamless journey of token migration from Goerli to Mumbai using the powerful fxPortal contracts. This project is your gateway to effortlessly transferring ERC721 tokens, unlocking a world of possibilities on the Mumbai network.

## 🛠️ Steps for Bridging
1. Installation: Begin by running npm i to effortlessly install the necessary dependencies.
2. Secure Your Keys: Safeguard your journey by placing your private key in the .env.examples file. Once done, simply rename it to .env for enhanced security.
3. Deployment Magic: Execute npx hardhat run scripts/deploy.js --network goerli to deploy the enchanting CuteCats contract.
4. Token Address Integration: Immerse yourself further by pasting the freshly deployed contract address into the tokenAddress variable for subsequent scripts.
5. Public Key Brilliance: Illuminate your path by ensuring your public key is in place, ready to shine.
6. NFT Minting Extravaganza: Engage in the exhilarating experience of running npx hardhat run scripts/batchMint.js --network goerli to mint NFTs directly to your wallet.
7. Approval & Deposit: Elevate your journey with npx hardhat run scripts/approveDeposit.js --network goerli to seamlessly approve and deposit your tokens onto the Polygon network.
8. Await the Marvel: Patience becomes a virtue as you wait for approximately 20-30 minutes for your NFTs to grace your Polygon account.
9. Verify & Revel: Head over to polyscan.com to verify your account and witness the tokens' arrival. Click on the transaction to unveil the contract address for your Polygon endeavors.

Embark on this adventure and witness the convergence of Goerli and Mumbai through the ERC721 Goerli to Mumbai Bridge with fxPortal. Your tokens are on the move, and the journey is as thrilling as the destination! 🌐✨







