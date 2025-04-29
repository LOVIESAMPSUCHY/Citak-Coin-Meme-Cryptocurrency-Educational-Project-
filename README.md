# Citak Coin

**Citak Coin** is an educational meme cryptocurrency project themed around a magical black cat wearing a wizard hat. This project is designed for learning purposes, demonstrating the basics of creating a BEP-20 token on Binance Smart Chain (BSC) and a simple website to accompany it. The project combines a fun theme with educational content to make learning about blockchain development engaging.

## About the Project

Citak Coin is a **meme coin** created to illustrate how a cryptocurrency can be built and launched. It is **not a real investment** and has no monetary value; instead, it's meant for experimentation, learning, and showcasing a token project from smart contract to front-end. The black cat in a wizard hat theme gives the project a whimsical identity, emphasizing that it's all about **magic and fun in crypto education**.

## Tokenomics

- **Token Name:** Citak Coin (CITAK)
- **Blockchain:** Binance Smart Chain (BSC) – BEP-20 standard token.
- **Total Supply:** 1,000,000,000 CITAK (1 billion tokens)
- **Decimals:** 18 (standard for ERC/BEP-20 tokens)
- **Distribution:**
  - 50% for community rewards and airdrops (to engage and educate participants).
  - 25% reserved for project development and future improvements.
  - 15% for initial liquidity (if deployed to a test or main network).
  - 10% for contributors and educational partners.

*Note:* These tokenomics are for educational demonstration. All tokens are initially minted to the deployer's address (as defined in the smart contract) and can be distributed according to the above allocations.

## Roadmap

1. **Concept & Planning (Q1 2025):** Idea of Citak Coin is born – define theme, tokenomics, and project scope. Set up the GitHub repository and draft initial smart contract, website, and documentation.
2. **Development (Q2 2025):** Write and test the smart contract on a testnet. Create a simple landing page and draft a whitepaper outline. Ensure everything is under an open-source MIT license for transparency.
3. **Testing & Deployment (Q3 2025):** Deploy Citak Coin smart contract on BSC Testnet for demonstration. Finalize the landing page and host it (e.g., via GitHub Pages or a simple web server) so that others can view the project.
4. **Community Engagement (Q4 2025):** Share the project with the community. Conduct educational airdrops on testnet, allowing users to claim some CITAK tokens to learn how transactions and wallets work. Gather feedback.
5. **Future Plans (Beyond):** If there's interest, consider launching on BSC mainnet in a limited capacity (still as an educational tool, perhaps with a charity or learning initiative). Expand the documentation into a full whitepaper and add more features (like an interactive dApp, NFT collectibles of the "Wizard Cat", etc.).

## Getting Started

To explore the Citak Coin project, you can follow these steps:

### Prerequisites

- A web browser to open the landing page.
- Optionally, [Node.js](https://nodejs.org/) and a simple HTTP server (or just use the browser directly) if you want to serve the website on `localhost`.
- For the smart contract, you'll need a Solidity development environment:
  - E.g., [Remix IDE](https://remix.ethereum.org/) (online) or a local setup with [Hardhat](https://hardhat.org/) or [Truffle](https://trufflesuite.com/).

### Running the Frontend (Landing Page)

The project includes a static landing page in the `frontend/` directory. You can open `frontend/index.html` directly in your web browser to view the site. All resources (CSS, image) are local, so it should display correctly without a web server. For a better experience (and if you'd like to avoid any browser restrictions on local files), you can serve the `frontend` folder using a simple web server. For example, using Node.js and npm:

```bash
npm install -g serve
serve frontend/
