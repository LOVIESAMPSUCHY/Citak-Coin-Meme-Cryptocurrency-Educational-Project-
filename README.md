Citak Coin – Magical Meme Coin (Educational Project)

(Polish version of this README is available in README_PL.md)

Introduction

Citak Coin is an educational meme cryptocurrency project built on the Binance Smart Chain. In the world of crypto, a meme coin (or memecoin) is a cryptocurrency inspired by an Internet meme or a humorous conce4】. This project was created to demonstrate how to develop and deploy a BEP-20 token using modern best practices. Citak Coin is a Binance Smart Chain (BSC) token following the BEP-20 standard (which is equivalent to Ethereum’s ERC-20 on BS2】. The project is open-source and geared towards learning; it is not an investment and holds no real monetary value.

Project Overview

This repository contains everything needed to launch the Citak Coin token and its informational website:

Smart Contract (contracts/CitakCoin.sol): A Solidity contract for a BEP-20 token, implemented with OpenZeppelin libraries for security and standard compliance.

Frontend Website (frontend/): A static landing page (HTML/CSS/JS) with a magical cat theme, featuring sections for About, Tokenomics, Roadmap, and Contact.

Logo (assets/logo.png): A placeholder logo image of a wizard cat representing the token’s meme theme.

Documentation (README.md, README_PL.md, docs/whitepaper.md, docs/whitepaper_PL.md): Project description, usage instructions, tokenomics, roadmap, and educational context (provided in both English and Polish).

License (LICENSE): MIT License open-source license file.

Configuration (package.json, optional index.js): Basic project info and placeholders for potential future enhancements (e.g., web3 integration script).

The structure is designed to be easy to navigate for newcomers. All code and content are intended for educational purposes and can be reused or modified freely under the MIT license.

Getting Started

Deploying the Smart Contract (BEP-20 Token)

To deploy the Citak Coin smart contract:

Open Remix IDE in your web browser. Ensure you have the Solidity compiler set to version 0.8.x (the contract uses pragma solidity ^0.8.0).

Create a new file in Remix (e.g., CitakCoin.sol) and paste the contents of contracts/CitakCoin.sol into it. Remix will automatically fetch the OpenZeppelin dependencies via the import statements.

Compile the contract. You should see 0 warnings and 0 errors if everything is correct.

Configure your environment for deployment:

For testing, switch Remix to Injected Web3 and connect your MetaMask (or another wallet) to the BSC Testnet (you may need to add the BSC Testnet network to MetaMask).

Obtain some test BNB from a faucet (e.g., the Binance Faucet for testnet). This will be used to pay gas fees on testnet.

For mainnet deployment, connect to BSC Mainnet in your wallet (ensure you have BNB for gas).

In Remix, go to the Deploy & Run Transactions panel. Select the CitakCoin contract and input the initialSupply parameter. This value should be the initial number of tokens (in whole units) you want to create. For example, to create 1,000,000,000 CITAK, enter 1000000000.

Click Deploy. Confirm the transaction in your wallet. Once mined, the contract will be deployed. The deploying address will receive the entire initial supply of CITAK tokens.

(Optional) Verify the contract on BscScan for transparency. Copy the contract address and use BscScan’s verification tool, selecting compiler 0.8.x and optimization if used. This step will publish the source code, allowing others to review the code on BscScan.

After deployment, you can interact with the token via BSC wallets. For example, add a custom token in MetaMask using the deployed contract address to see your CITAK token balance.

Running the Frontend Website

The website is completely static, so no special build steps are required. You can open frontend/index.html directly in a web browser to view the landing page. For a better experience (and to allow future expansion), you might serve it using a simple HTTP server (e.g., using Python’s http.server or an extension like Live Server in VSCode).

Key sections of the page:

About: Overview of what Citak Coin is.

Tokenomics: Details on supply and distribution.

Roadmap: Timeline of project milestones.

Contact: Contact information (email, Twitter, GitHub).

Because this is a demo project, the contact links are placeholders. Feel free to update them to real contacts if you fork this project.

Deploying the Website to GitHub Pages

You can host the Citak Coin landing page using GitHub Pages:

Option 1 – docs folder: Move or copy the contents of the frontend/ folder into a docs/ folder at the root of this repository (or configure GitHub Pages to use the existing frontend folder as the site source). Then, in the repository settings on GitHub, enable GitHub Pages and set the source to the docs/ folder (or to the main branch root if you placed the files there). GitHub will publish the site at https://<your-username>.github.io/<repository-name>/.

Option 2 – gh-pages branch: Create a separate branch named gh-pages and commit the frontend site files there. You can use the gh-pages npm package to deploy automatically. After pushing, enable GitHub Pages to serve from the gh-pages branch in settings.

After deploying, test the page via the GitHub Pages URL. The static site should load with the styling and you can navigate to each section. Ensure the logo and any assets load correctly (you might need to adjust paths if using a different folder structure).

Tokenomics

Token Name: Citak CoinSymbol: CITAKNetwork: Binance Smart Chain (BEP-20)Total Supply: 1,000,000,000 CITAK

All tokens are minted upon deployment to the deployer’s address (the owner). The token distribution is planned as follows:

50% – Community & Airdrops: Reserved for community distribution through airdrops or educational rewards.

20% – Development Team: Held by the project team to fund development and educational initiatives (e.g., creating tutorials, workshops).

20% – Liquidity Pool: Set aside for providing liquidity on a decentralized exchange (e.g., PancakeSwap) if demonstrating trading or listing the token.

10% – Marketing & Partnerships: To be used for promoting the project, partnerships with educational platforms, or other outreach.

Note: These allocations are not enforced by the smart contract code (which simply mints the total supply to the owner). It is up to the project administrators to distribute the tokens according to the plan above. Since Citak Coin is educational, these numbers are illustrative.

The CITAK token itself has 18 decimal places (like most ERC-20/BEP-20 tokens). This means that internally, the smallest unit is 1e-18 of a token. When specifying the initial supply in the contract, remember that the contract multiplies the given number by 10^18 to get the total units.

Roadmap

The development roadmap for Citak Coin outlines the planned phases of the project:

Q1 2025 – Launch Phase: Design the concept, develop the smart contract, create the website and branding (wizard cat theme), and prepare bilingual documentation (whitepaper and README).

Q2 2025 – Testnet Release: Deploy Citak Coin on the BSC Testnet for trial. Share the project with a small community of learners. Collect feedback, improve documentation, and ensure the token contract is functioning as expected (transfers, etc.).

Q3 2025 – Mainnet Deployment: Deploy the token on BSC Mainnet. Distribute a portion of tokens to community members (simulating an airdrop). Begin building a broader awareness for the project in educational circles.

Q4 2025 – DEX Listing Demonstration: List Citak Coin on a decentralized exchange like PancakeSwap to demonstrate how providing liquidity and trading works. This includes creating a liquidity pool with the reserved tokens. Emphasize to participants that this is a demonstration only.

2026 – Future Plans: Explore additional features such as governance (e.g., allowing token holders to vote on certain decisions) or non-fungible tokens (perhaps a series of wizard-cat NFTs) to expand the educational scope. Continuously update the curriculum and guides associated with Citak Coin.

Each phase of the roadmap is focused on education and community engagement rather than speculative investment. The timeline can be adjusted as needed to fit educational program schedules or participant pace.

Educational Context and Goals

Citak Coin is primarily a learning tool. By building this project, contributors and users can learn:

How to write and deploy a smart contract on BSC (using Solidity and OpenZeppelin).

How to create a simple frontend that interacts (even minimally) with a blockchain project.

Best practices for documenting a crypto project (writing a README and whitepaper).

How to manage an open-source project and publish it (including licensing and deployment).

The project demonstrates how blockchain technology can be taught in a fun and engaging way. We chose Binance Smart Chain for its low transaction fees and ease of use for newcome5】. We utilized OpenZeppelin contracts because they are a secure industry standa0】, which reduces the risk of vulnerabilities and follows established conventions.

Disclaimer: Citak Coin is not a real investment. It has no financial value and is not listed on any exchanges in a production capacity. All activities with Citak Coin are for demonstration and educational practice. Always exercise caution and do not send real funds expecting any return.

License

This project is open source under the MIT License. See the LICENSE file for details. This means you can copy, modify, and use the code and content freely for your own learning or projects, as long as you include the original license notice.

Contributing

Contributions are welcome! If you have ideas to improve the code, documentation, or examples, feel free to fork the repository and open a pull request. You can also open issues for bug reports or requests for enhancements.

By participating, you agree to uphold our educational goals and keep the project friendly for beginners. All constructive input is appreciated.

Contact

For any questions or collaboration inquiries, you can reach out via:

Email: suchysuchomsky29@gmail.com



GitHub: Project Repository

(The above contacts are provided as examples for this educational project.)
