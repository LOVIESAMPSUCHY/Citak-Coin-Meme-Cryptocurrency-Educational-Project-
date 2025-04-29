Super, Mateusz. Przygotuję kompletne repozytorium GitHub dla projektu Citak Coin: zawierające pełne README.md, smart kontrakt BEP-20 w Solidity, profesjonalny landing page `index.html` z sekcjami (about, tokenomics, roadmap, kontakt) oraz strukturę katalogów z grafiką logo.

To będzie projekt, którym z dumą będziesz mógł się pochwalić rekruterom i na LinkedInie.

# Citak Coin – Meme Cryptocurrency (Educational Project)

 ([Download Halloween, Cat, Witch Hat. Royalty-Free Stock Illustration Image - Pixabay](https://pixabay.com/illustrations/halloween-cat-witch-hat-icon-5586567/)) *Figure: A cheerful cat in a wizard hat serves as the mascot for Citak Coin, blending magic and meme culture.*  

**Citak Coin** is a conceptual meme cryptocurrency project built on Binance Smart Chain (BSC) as a BEP-20 token. It features a playful **black cat in a wizard’s hat** as its mascot and is created for educational purposes and portfolio demonstration. Meme coins are known for leveraging internet humor and community trends ([Meme Coins: Examples of What They Are, Pros and Cons, and How to Make Them](https://www.investopedia.com/meme-coin-6750312#:~:text=Definition)), and Citak Coin embraces this spirit while showcasing a professional project structure. The token is implemented on BSC using the BEP-20 standard (analogous to Ethereum’s ERC-20 ([BEP-20 vs ERC-20: Features, Use Cases, and Differences - HeLa](https://helalabs.com/blog/bep-20-vs-erc-20-comparative-guide-to-blockchain-token-standards/#:~:text=BEP,unique%20functionalities%20and%20use%20cases))) to take advantage of familiar token infrastructure. This project is **not a real investment opportunity** but a **learning exercise** – intended to demonstrate skills in smart contract development, web design, and project documentation.

## Project Overview

Citak Coin is presented as a complete GitHub repository and static landing page, designed to look professional and be ready for deployment. The project includes all key components one would expect in a real-world crypto project, organized in a clean repository structure. Everything is written in **English** and released under the **MIT License** for open-source use. The main elements of the project are:

- **Smart Contract:** A BEP-20 token contract (`CitakCoin.sol`) using OpenZeppelin libraries for security and standard compliance. The token is named **Citak Coin (CITAK)**, with a fixed supply of 1 billion units and 18 decimal places (standard for ERC20/BEP20 tokens).
- **Frontend Landing Page:** A static **HTML/CSS** website (`index.html` and `styles.css`) with a dark, magical theme to match the meme mascot. It has sections for **About**, **Tokenomics**, **Roadmap**, and **Contact**, providing a quick overview of the project.
- **Assets:** An `assets/` folder containing the Citak Coin logo (the black wizard cat emblem) and any other static images or media.
- **Documentation:** A `README.md` file covering all important details (project description, inspiration, tokenomics, roadmap, usage instructions, etc.), and a `docs/whitepaper.md` which serves as a **whitepaper template** to be expanded in the future. The documentation clarifies that this is a conceptual project created for learning, not an actual token launch.

The project’s aim is to simulate a full-stack blockchain application in a simplified form. By including a smart contract and a frontend side by side, Citak Coin demonstrates how a cryptocurrency concept can be packaged professionally for presentation to potential employers or clients. In the sections below, each component of the repository is detailed, including file structure and example content.

## Repository Structure

The repository is organized into directories for each part of the project, making it easy to navigate. Below is an overview of the structure with a brief description of each item:

- **`README.md`** – Comprehensive documentation of the project. Explains what Citak Coin is, the inspiration behind it, tokenomics, roadmap, how to run the project, and the conceptual nature of the project. Serves as the front page of the GitHub repository.
- **`contracts/`** – Directory for smart contracts (Solidity files).
  - `CitakCoin.sol` – The main smart contract implementing the CITAK token (BEP-20). Based on OpenZeppelin’s ERC20 contract for reliability. Includes inline comments to explain the code.
- **`frontend/`** – Directory for the landing page source code.
  - `index.html` – The HTML file for the single-page landing website. It has sections: About, Tokenomics, Roadmap, Contact, and includes the project’s branding (logo and name).
  - `styles.css` – The CSS stylesheet for styling the landing page in a dark theme (e.g., dark background, light text, and purple/magical accents to match the wizard cat vibe).
- **`assets/`** – Static assets for the project.
  - `logo.png` – The Citak Coin logo image (the black cat with wizard hat). Used in the website and possibly in documentation.
  - *(Any other images or icons would reside here as needed.)*
- **`docs/`** – Additional project documentation.
  - `whitepaper.md` – A draft template of a whitepaper for Citak Coin. Contains an outline that can be expanded to a full whitepaper, including sections like Introduction, Technology, Tokenomics, Roadmap, and Conclusion.
- **`LICENSE`** – *(If included)* MIT License text, specifying the open-source license for the project. (Also, the smart contract file includes an SPDX license identifier declaring MIT.)

This structure follows common conventions for blockchain projects: smart contracts separated from frontend code, and dedicated folders for assets and docs. A potential employer reviewing the repository can easily find the contract, view the live demo page (via GitHub Pages or by opening the HTML), and read documentation to understand the project.

## Project Documentation (README.md)

The `README.md` is the centerpiece of the repository’s documentation. It provides context and instructions, ensuring that anyone who stumbles upon the project can quickly grasp its purpose and how to use it. Below is a breakdown of the main sections included in the README:

### Description and Inspiration

This section introduces **Citak Coin** as a meme-inspired cryptocurrency project. It explains that the project draws inspiration from popular meme coins like Dogecoin and Shiba Inu, which showed how humor and internet culture can build passionate communities ([Meme Coins: Examples of What They Are, Pros and Cons, and How to Make Them](https://www.investopedia.com/meme-coin-6750312#:~:text=Definition)). The choice of a **wizard cat mascot** adds a unique twist – blending the mystery of magic with the internet’s love for cats and memes. The README makes it clear that Citak Coin is a **concept project for educational purposes**. In a professional tone, it might say for example:

> *“Citak Coin is a fictional meme cryptocurrency on Binance Smart Chain, created as an educational project. It combines blockchain technology with a fun theme – a wizard-hat-wearing black cat – to explore how community-driven meme coins operate. This project was inspired by the success of meme coins in engaging communities and is designed to demonstrate smart contract and web development skills in a cohesive portfolio piece.”*

By framing it this way, the README conveys **why the project exists (learning and showcasing skills)** and how it connects to real-world trends in crypto (the meme coin phenomenon).

### Tokenomics

Here, the README outlines the **tokenomics** of the CITAK token – essentially the characteristics and rules of the token. Since this is a simple token, the tokenomics section covers:

- **Name & Symbol:** Citak Coin (CITAK)
- **Blockchain:** Binance Smart Chain (BEP-20 standard token) ([BEP-20 vs ERC-20: Features, Use Cases, and Differences - HeLa](https://helalabs.com/blog/bep-20-vs-erc-20-comparative-guide-to-blockchain-token-standards/#:~:text=BEP,unique%20functionalities%20and%20use%20cases))
- **Total Supply:** 1,000,000,000 (1 billion tokens)
- **Decimals:** 18 (standard divisibility, allowing fractional tokens)
- **Contract Address:** *\(To be provided if deployed; for now, this is a concept so maybe a placeholder or testnet address.\)* 
- **Ownership:** All tokens are initially minted to the deployer’s address (as this is an educational token with no public sale). No special allocation or vesting – this project assumes a fair distribution could be done by airdrop or community faucets if it were real.
- **Utility:** As a meme coin project, CITAK’s primary “utility” is community engagement and learning. (In a real scenario, meme coins often have no inherent utility beyond trading and community memes ([Meme Coins: Examples of What They Are, Pros and Cons, and How to Make Them](https://www.investopedia.com/meme-coin-6750312#:~:text=Meme%20coins%20are%20cryptocurrencies%20created,of%20community%20to%20attract%20users)), which is acknowledged here to keep expectations clear.)

The README might list these as bullet points or in a table for clarity. For example:

```markdown
**Token Name:** Citak Coin  
**Symbol:** CITAK  
**Network:** BSC (Binance Smart Chain), BEP-20 token  
**Total Supply:** 1,000,000,000 CITAK  
**Decimals:** 18  
**Contract:** Deployed to BSC Testnet (0x1234...abcd) *(example)*  
```

It also mentions that the token has no innovative mechanics like burn fees or reflection – it’s a plain vanilla token to keep the focus on the fundamental structure. This simplicity is intentional given the project’s educational scope.

### Roadmap

The roadmap in the README outlines the planned (or hypothetical) milestones for the project’s development. Even though Citak Coin is conceptual, including a roadmap demonstrates the ability to plan project phases and gives a narrative of progress. A possible roadmap is:

1. **Q1 2025 – Project Inception:** Idea conceived, mascot and theme decided (wizard cat meme). Smart contract development on BSC Testnet, basic token functionality achieved.
2. **Q2 2025 – Launch of Website:** Development of the landing page and branding materials. Set up GitHub repository with README, code, and whitepaper template. Publish the site via GitHub Pages for demo purposes.
3. **Q3 2025 – Community Building (Hypothetical):** If this were a real project, this phase would focus on community engagement – e.g., social media presence, airdropping test tokens, gathering feedback.
4. **Q4 2025 – Future Features (Hypothetical):** Exploration of additional features like governance (DAO integration), NFTs of the cat mascot, or utility in a simple game – reinforcing that this is where the project could go if it continued.
5. *(Beyond)* – **Educational Expansion:** Write a detailed whitepaper (filling out the `docs/whitepaper.md`), and perhaps tutorials or blog posts about what was learned by building Citak Coin.

Each point in the roadmap is kept fairly high-level. The README will also stress that phases beyond Q2 2025 are **hypothetical** since the project is not actually launching a product, but it shows foresight and an understanding of how a crypto project might evolve.

### Repository Structure & Contents

The README also includes a section (as summarized earlier) that explains the repository layout. This acts as a guide for anyone browsing the code. For example:

- **Contracts:** location of Solidity code.
- **Frontend:** HTML/CSS for the site.
- **Assets:** images like the logo.
- **Docs:** the whitepaper outline.
- **Tests:** *(If there were any tests or scripts, though not mentioned in requirements, we could note them. In this project, testing might be manual via deploying the contract in Remix or Hardhat.)*

By listing this, the README ensures that a recruiter or reader knows where to find each piece of the project in the GitHub repo.

### Setup and Usage Instructions

Even though this project is conceptual, the README provides instructions to run the components locally:

- **Smart Contract Deployment:** Instructions for deploying or testing the contract on a local blockchain or testnet. For example, “To test the smart contract, you can use [Remix](https://remix.ethereum.org/) with the Solidity compiler v0.8.x. Simply copy the code from `contracts/CitakCoin.sol` into Remix, compile, and deploy it on the Binance Smart Chain testnet (or any EVM-compatible network). Ensure you have a BSC testnet wallet configured (e.g., via MetaMask) and some test BNB for gas. The contract should mint the total supply to your address upon deployment.” This kind of step-by-step helps demonstrate how someone could reproduce the deployment. Advanced users could also use Truffle or Hardhat – the README might mention those as alternatives for local deployment or automated testing.
- **Running the Frontend:** Since the frontend is static, the instructions are straightforward: “Open the `frontend/index.html` file in a web browser to view the site. For a better experience, you can serve it using a simple HTTP server (for example, Python’s `http.server` or a VSCode Live Server) to simulate hosting. On GitHub Pages, the site can be hosted by moving the contents of `frontend/` to the repository’s `gh-pages` branch or the `docs/` folder.” This explains how to get the landing page up and running.
- **Viewing the Project Online:** Optionally, if the repository is published with GitHub Pages, the README would include a link to the live demo of the site (e.g., `https://username.github.io/CitakCoin/`). For now, one can imagine this as a future enhancement or something the user would do after assembling the repo.
- **Interacting with the Token:** If applicable, instructions for interacting with the token could be given. For instance, “After deploying, you can add the token to your MetaMask wallet using the contract address. You can also interact with it using BSC’s testnet explorer or a tool like MyCrypto by invoking standard ERC-20 methods (transfer, balanceOf, etc.).” This is not strictly necessary for a conceptual project, but it shows thoroughness in how one would use the token if it were live.

By including these instructions, the README shows that the author understands not just how to code the project, but how to *use* and demonstrate it – a crucial point for portfolio projects.

### Disclaimer

Finally, very importantly, the README contains a **disclaimer** or note clarifying the nature of the project. It should state that **Citak Coin is a conceptual and educational project** with no real monetary value. For example:

> *“**Note:** This project is for **educational purposes** only. Citak Coin is a concept token and has **no real-world value** or active trading. The smart contract is deployed on a test network for demonstration, and the website is a static mock-up. This project should **not** be interpreted as an endorsement to invest in any real cryptocurrency. It is meant to showcase development skills in blockchain and web technologies.”*

This protects the author (and any viewers) by making the intent clear, and it also demonstrates professionalism by anticipating ethical considerations.

### License

At the end of the README (or in a dedicated LICENSE file), the project’s open-source license is stated. Citak Coin uses the **MIT License**, which is a permissive license allowing others to reuse the code freely with attribution. The README might simply say:

> **License:** This project is open-source under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use or adapt the code for your own learning and projects.

Including the SPDX identifier in the smart contract (`// SPDX-License-Identifier: MIT`) and a LICENSE file in the repo reinforces this.

Overall, the README.md is written in clear, professional English, with a structure that covers all requested aspects: description, inspiration, tokenomics, roadmap, setup instructions, and a note on the project’s conceptual nature. It serves as both an introduction and a manual for the Citak Coin project.

## Smart Contract – `contracts/CitakCoin.sol`

The **CitakCoin smart contract** implements the token on Binance Smart Chain using Solidity. It follows the BEP-20 standard, which in practice is identical to the Ethereum ERC-20 token standard ([BEP-20 vs ERC-20: Features, Use Cases, and Differences - HeLa](https://helalabs.com/blog/bep-20-vs-erc-20-comparative-guide-to-blockchain-token-standards/#:~:text=BEP,unique%20functionalities%20and%20use%20cases)). By leveraging OpenZeppelin’s well-audited libraries, the contract ensures compliance with standard behavior and security best practices.

Key characteristics of the CitakCoin contract:
- **Total Supply:** 1,000,000,000 CITAK are created at deployment.
- **Decimals:** 18 (meaning the smallest unit is 10^-18 of a token, as typical for ERC20/BEP20).
- **Initial Distribution:** The entire supply is minted to the deployer (the account that deploys the contract). From there, tokens could be distributed as desired (for example, manual transfers to others to simulate an airdrop or initial distribution).
- **Token Name and Symbol:** Set to “Citak Coin” and “CITAK” respectively.
- **Standards Used:** Inherits from OpenZeppelin’s `ERC20` contract, which already implements all standard functions like transfer, approve, transferFrom, etc. The contract also uses the `ERC20` constructor to set token name and symbol. (No custom functions beyond the constructor are added, keeping it simple.)

The contract is kept minimal intentionally. Many real-world tokens might add extra functionality (ownership control, the ability to burn or mint new tokens, fee mechanisms, etc.), but those are outside the scope of this basic meme coin. Simplicity makes it easier to understand and reduces potential errors – an important consideration in smart contract development.

Below is an example implementation of `CitakCoin.sol` with comments explaining each part:

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Import the OpenZeppelin ERC20 implementation.
// OpenZeppelin Contracts is a library of secure smart contract components.
import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

/**
 * @title CitakCoin
 * @dev Citak Coin (CITAK) - a simple BEP-20 token on Binance Smart Chain.
 * This contract mints a fixed supply of 1 billion CITAK tokens to the deployer's address.
 * It extends OpenZeppelin's ERC20 contract to utilize standard token functionality securely.
 */
contract CitakCoin is ERC20 {
    /**
     * @dev Constructor that gives msg.sender all initial tokens.
     * The ERC20 constructor is called with the token name and symbol.
     * By default, ERC20 sets decimals to 18, which is standard for tokens.
     */
    constructor() ERC20("Citak Coin", "CITAK") {
        // _mint is an internal function in ERC20 that creates tokens.
        // Here we create 1,000,000,000 * (10^18) units (which equals 1 billion tokens with 18 decimals)
        // and assign them to the account that deploys the contract (msg.sender).
        _mint(msg.sender, 1000000000 * 10 ** decimals());
    }
}
```

In the code above, we see a very straightforward token creation. Notable points explained by the comments:

- The `// SPDX-License-Identifier: MIT` line at the top indicates the source code license (MIT in this case), which is a standard practice in Solidity source files.
- `pragma solidity ^0.8.0;` specifies the Solidity compiler version. Using a modern version (0.8.x) is important for safety (it has built-in overflow checks, etc.).
- The import statement brings in the ERC20 contract code from OpenZeppelin. This assumes the OpenZeppelin library is available in the project (if using a tool like Hardhat or Truffle, one would install the `openzeppelin-contracts` npm package; in Remix, one can import via URL).
- The `contract CitakCoin is ERC20` means our contract inherits all the functionality of ERC20. We only need to define the constructor to set up initial state.
- In the `constructor()`, we call the ERC20 constructor with the token name and symbol. OpenZeppelin’s ERC20 sets the `decimals` to 18 by default, and we rely on that (not overriding `decimals()` means it stays at 18).
- The `_mint(msg.sender, 1000000000 * 10 ** decimals());` line creates the total supply. `decimals()` returns 18, so `10 ** decimals()` is 10^18. Multiplying 1,000,000,000 by 10^18 gives the number of the smallest indivisible units to mint. This results in 1e9 tokens. All of them are assigned to `msg.sender` (the deployer).
- Because we inherit from ERC20, our CitakCoin contract automatically has functions like `balanceOf(address)`, `transfer(to, amount)`, `approve(spender, amount)`, etc., without explicitly writing them. This is part of **OpenZeppelin’s advantage** – it provides battle-tested code for these standard functions, reducing the likelihood of bugs.

This contract could be deployed on the BSC network (or any Ethereum-compatible network). Once deployed, anyone with the contract address could interact with it as they would with any ERC20/BEP20 token – sending tokens, checking balances, etc. The simplicity makes it easy to verify and understand, which is ideal for an educational project.

## Frontend – Landing Page Website

The frontend of the Citak Coin project is a static **landing page** that introduces the token’s concept in a visually appealing way. It’s crafted with basic HTML and CSS (no frameworks, keeping it lightweight) and follows a **dark theme** consistent with the magical cat mascot. The landing page is meant to be deployable via GitHub Pages or similar static hosting, so it doesn’t rely on any backend or server-side code.

**Design & Sections:** The page includes the following sections, typically arranged vertically as one scrolls down:

- **Hero/Header:** At the top, the Citak Coin logo (the cat wizard) and the project name, possibly with a tagline. This immediately gives visitors the theme of the project.
- **About:** A section describing what Citak Coin is, echoing the description from the README but in a more marketing-friendly tone – for instance, a punchy slogan or mission statement followed by a brief paragraph.
- **Tokenomics:** A section that highlights the key token facts (total supply, symbol, network, etc.), possibly using icons or simple infographics alongside text.
- **Roadmap:** A timeline or list of phases (like the one described in the README), giving a visual sense of how the project would progress.
- **Contact:** A final section with contact information or calls to action. Since this is a demo, it might simply encourage viewers to check out the GitHub repository or contact the creator on LinkedIn/GitHub. It could include an email link or placeholder socials.

The styling is intended to be clean and modern, using a dark background (for example, a deep navy or black) with light text. Accents might be in purple or violet (to match the wizard theme) and maybe a contrasting color like gold or white for important highlights. The font choices would be simple (system sans-serif or a Google Font if desired).

### `index.html`

Below is a simplified example of the `frontend/index.html` content. It demonstrates the structure and content of the landing page:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Citak Coin – Meme Magic on BSC</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <!-- Header/Hero section -->
  <header>
    <!-- Logo image -->
    <img src="../assets/logo.png" alt="Citak Coin Logo" class="logo" />
    <h1>Citak Coin</h1>
    <p class="tagline">A Magical Meme Cryptocurrency on BSC</p>
    <!-- Simple navigation menu (anchors to sections) -->
    <nav>
      <a href="#about">About</a>
      <a href="#tokenomics">Tokenomics</a>
      <a href="#roadmap">Roadmap</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About</h2>
    <p>
      Citak Coin is a <strong>meme-inspired cryptocurrency</strong> featuring a mischievous black cat wizard as its mascot. 
      Created as an <em>educational project</em> on Binance Smart Chain, Citak Coin demonstrates how a fun concept can be turned into a complete crypto project – from a smart contract to a user-friendly website.
    </p>
    <p>
      <strong>Mission:</strong> To bring a touch of magic and humor to blockchain education. Citak Coin is <u>not an investment</u>, but a demonstration of technology and creativity working together.
    </p>
  </section>

  <!-- Tokenomics Section -->
  <section id="tokenomics">
    <h2>Tokenomics</h2>
    <ul>
      <li><strong>Token Name:</strong> Citak Coin</li>
      <li><strong>Symbol:</strong> CITAK</li>
      <li><strong>Network:</strong> BSC (BEP-20)</li>
      <li><strong>Total Supply:</strong> 1,000,000,000 tokens</li>
      <li><strong>Decimals:</strong> 18</li>
      <li><strong>Contract:</strong> <span class="contract-address">0x0123...4567</span> <em>(Testnet)</em></li>
    </ul>
    <p class="small-note">*Citak Coin is a demo token. These parameters are for a concept project.*</p>
  </section>

  <!-- Roadmap Section -->
  <section id="roadmap">
    <h2>Roadmap</h2>
    <ol>
      <li><strong>Q1 2025:</strong> Concept design, smart contract development, and initial testing on testnet.</li>
      <li><strong>Q2 2025:</strong> Launch of the Citak Coin website and branding. Publish code and demo for the community.</li>
      <li><strong>Q3 2025:</strong> Community engagement (social media, token airdrop events on testnet).</li>
      <li><strong>Q4 2025:</strong> Exploration of new features (governance, NFTs of the mascot, etc.) and writing a detailed whitepaper.</li>
    </ol>
    <p class="small-note">*This roadmap is hypothetical and for demonstration purposes.*</p>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Interested in the project or have questions? Get in touch with the creator:</p>
    <p>
      <strong>Email:</strong> <a href="mailto:citakcoin@example.com">citakcoin@example.com</a><br/>
      <strong>GitHub:</strong> <a href="https://github.com/yourusername/CitakCoin">yourusername/CitakCoin</a>
    </p>
    <p>
      You can also find more information and the code on the <a href="https://github.com/yourusername/CitakCoin">GitHub repository</a>.
    </p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Citak Coin – This project is for educational purposes only.</p>
  </footer>
</body>
</html>
```

In this HTML file:

- We use semantic sections (`<section>` with ids) for each part of the page so that the nav links can anchor to them.
- The header contains the logo (assuming `logo.png` is placed in an `assets` directory one level up; if the site were hosted via GitHub Pages in the same repository, the path might be adjusted accordingly). It also contains a navigation menu with links that jump to different sections of the page.
- Content in each section is kept simple:
  - The About section provides a high-level description and mission statement.
  - The Tokenomics section uses a list (`<ul>`) to neatly itemize token parameters. We included a placeholder for a contract address (as an example, one might deploy it on BSC testnet and put the address here). A small note clarifies it’s a demo token.
  - The Roadmap section uses an ordered list (`<ol>`) to enumerate the timeline. Each list item has a bold phase label and a description.
  - The Contact section gives an email and a link to the GitHub repo (the actual username/repo should be replaced with the real ones when used). It invites interaction or questions.
- A footer at the bottom reiterates the educational nature of the project.

This HTML can be viewed on any browser. It doesn’t require any JavaScript to function. It’s purely informational, as is typical for a landing page that introduces a crypto project (actual app functionality like a token swap or dashboard is not needed here, since our focus is just presentation).

### `styles.css`

The CSS file styles the HTML content to create the dark, magical theme. It defines colors, layout, and responsive behavior to ensure the site looks good on various screen sizes. Below is an example of what `frontend/styles.css` might contain:

```css
/* Basic reset and font settings */
body {
  margin: 0;
  padding: 0;
  background-color: #101010;      /* dark background */
  color: #e0e0e0;                 /* light gray text for contrast */
  font-family: Arial, sans-serif; /* clean, sans-serif font */
  line-height: 1.6;
}

/* Header (hero section) styling */
header {
  text-align: center;
  padding: 2rem 1rem;
  background: #181818;
}
header .logo {
  width: 120px;
  margin-bottom: 1rem;
}
header h1 {
  font-size: 2.5rem;
  margin: 0.2rem;
  color: #f0c040; /* a gold-ish color for the title to stand out */
}
header .tagline {
  font-size: 1.2rem;
  color: #cccccc;
  margin-bottom: 1.5rem;
}
/* Navigation links in header */
nav a {
  display: inline-block;
  margin: 0 1rem;
  color: #bbbbbb;
  text-decoration: none;
  font-weight: bold;
}
nav a:hover {
  color: #ffffff;
}

/* Section styles */
section {
  padding: 2rem 1rem;
  max-width: 800px;
  margin: 0 auto;
}
section h2 {
  font-size: 1.8rem;
  margin-bottom: 1rem;
  color: #bb86fc; /* a soft purple accent for section titles */
  text-align: center;
  text-transform: uppercase;
  border-bottom: 2px solid #333;
  display: inline-block;
  padding-bottom: 0.5rem;
}
/* Paragraphs inside sections */
section p {
  margin-bottom: 1rem;
  text-align: justify;
}
/* Specific styles for Tokenomics list */
#tokenomics ul {
  list-style: none;
  padding: 0;
  margin: 0 0 1rem 0;
}
#tokenomics li {
  background: url('data:image/svg+xml;utf8,<svg fill=\"%23bb86fc\" viewBox=\"0 0 16 16\" xmlns=\"http://www.w3.org/2000/svg\"><circle cx=\"8\" cy=\"8\" r=\"4\"/></svg>') no-repeat left center;
  /* Using a small purple dot as bullet via SVG data URI */
  padding: 0.3rem 0.5rem 0.3rem 1.5rem;
  margin: 0.2rem 0;
}
#tokenomics .small-note {
  font-size: 0.9rem;
  color: #999999;
}
/* Roadmap list styling */
#roadmap ol {
  counter-reset: step;
  padding-left: 1.2rem;
}
#roadmap li {
  margin: 0.5rem 0;
}
#roadmap li::before {
  counter-increment: step;
  content: counter(step) ". ";
  color: #f0c040;  /* gold color for numbers */
  font-weight: bold;
}
/* Contact links */
#contact a {
  color: #bb86fc;
  text-decoration: none;
}
#contact a:hover {
  text-decoration: underline;
}
/* Footer styling */
footer {
  text-align: center;
  padding: 1rem;
  background: #181818;
  color: #555555;
  font-size: 0.9rem;
}
```

Explanation of some stylistic choices:

- We set a dark background (`#101010` which is near-black) and a light text color (`#e0e0e0` a light gray) for good contrast without being stark white on black (which can be high contrast).
- The header has a slightly different background (`#181818`, a bit lighter black) to distinguish it from the rest of the page. The project title is given a gold-like color (`#f0c040`) to make it pop, reflecting perhaps the "treasure" or valuable aspect of coins. The tagline and nav links use shades of gray to not distract too much.
- Navigation links change color on hover for a simple interactivity cue.
- Sections have a max-width of 800px to avoid lines being too long on large screens, and are centered with auto margins. Padding gives breathing room.
- Section titles (h2) are styled with an uppercase transformation and a bottom border to set them apart. We used a purple (`#bb86fc`, inspired by a shade of purple associated with Material design dark themes) for these headers, tying back to the magical theme.
- In the Tokenomics section, we removed the default bullets and instead used a custom SVG circle as a bullet with the same purple color – this is a nifty trick to style list bullets. Each tokenomic item is a single line with bold label and normal text value.
- Roadmap uses an ordered list, but we styled the numbers with CSS counters to have a custom color and bold format. This makes the roadmap steps visually distinct.
- Contact links are purple to indicate interactivity and match the accent color; they underline on hover.
- The footer uses a smaller font and a gray color to deemphasize it, simply noting the project’s educational nature.

The CSS is written to be easily understandable. Comments could be added to the CSS (not shown above to keep it concise) to explain each section of styles, which is helpful for an educational project to show understanding of each rule.

This simple CSS should result in a visually pleasing one-page site. Because it’s all static, a viewer can scroll to read about the project, see the parameters, and know how to contact or find more info. The dark theme with purple and gold accents conveys a sense of mystique and fun, aligning with the idea of a magical cat meme coin.

Lastly, some responsiveness: The design as given is mostly flexible (text and blocks will shrink to fit smaller screens). If needed, media queries could be added for very small screens (e.g., making the header text slightly smaller on phones, or stacking nav links vertically), but given the simplicity, it likely displays fine on mobile by default. Ensuring the `<meta name="viewport" content="width=device-width, initial-scale=1.0">` tag is present (as it is) means it will scale appropriately on mobile devices.

## Assets and Whitepaper Template

**Assets (`assets/`):** The project includes an assets folder meant to contain images and other media. The primary asset is the Citak Coin **logo** – presumably an image of the black cat mascot with the wizard hat. In our example, we used a placeholder `logo.png`. For a real project, one might design a custom logo. The image we showed at the top of this document is an example of the style of illustration that could serve as a logo or mascot artwork. This logo is used in the website’s header. Keeping the asset in a dedicated folder makes it easy to manage and replace if the design is updated. If there were additional graphics (for example, an icon for the token or illustrations for the website), they would also reside in `assets/`.

**Whitepaper (`docs/whitepaper.md`):** A whitepaper is a detailed document that outlines the problem, solution, technology, and plans for a project. For Citak Coin, the whitepaper is not fully written (since this is a concept project), but a **template** is provided as a starting point. This demonstrates how one would organize thoughts for a future expansion of the project’s documentation. The `docs/whitepaper.md` likely contains an outline like:

```markdown
# Citak Coin Whitepaper (Draft)

## Introduction
Citak Coin is a meme-inspired cryptocurrency created as a conceptual project on Binance Smart Chain. *(This section will introduce the project, its background, and the goals.)*

## Background and Inspiration
*(To be developed: discuss meme coins, why a cat wizard theme, references to Dogecoin/Shiba Inu phenomenon.)*

## Technology
*(To be developed: details about BSC, BEP-20 standard, smart contract specifics, any technical unique points.)*

## Tokenomics
*(To be developed: elaborate on supply, distribution plan if any, economic model, comparisons to other meme coins.)*

## Roadmap
*(To be developed: a more detailed roadmap, possibly with technical milestones, community milestones, etc.)*

## Conclusion
*(To be developed: closing thoughts, vision for the project if it were to be launched, and the learning outcome of this project.)*
```

In the above template, each section is noted as “to be developed,” indicating where future content would go. This is useful for showing that the author knows what a whitepaper typically contains, even if they haven’t written it fully. It’s also a convenient place to later expand the project if desired – for instance, turning the concept into a more fleshed-out hypothetical scenario.

The whitepaper template is kept in the `docs` folder. This is deliberate because GitHub often can be configured to serve a documentation site from there, or simply to keep the repository root clean. Also, if using GitHub Pages, the `docs/` folder can double as the source for the site; however, in this project we are using `frontend/` for the site, so `docs/` strictly holds documentation.

## Conclusion

Citak Coin’s repository is now a **complete package**: it has a clear README, a properly commented smart contract, a styled landing page, visuals, and even a draft whitepaper. All content is in English and the project is under the MIT License, meaning it can be shared freely. This kind of project is excellent for showcasing a range of skills – from Solidity programming to web design and technical writing.

By creating Citak Coin in this manner, we demonstrate how one might present a **meme coin concept in a professional format**, suitable for a portfolio or as a learning artifact. Recruiters or clients viewing this project should get a clear sense that the author understands how to structure a software project, write clean code, and document it thoroughly.

**Sources:**

- Investopedia – Definition of Meme Coins ([Meme Coins: Examples of What They Are, Pros and Cons, and How to Make Them](https://www.investopedia.com/meme-coin-6750312#:~:text=Definition)) (insight into the role of humor and community in meme cryptocurrencies).
- HeLa Labs Blog – Explanation of BEP-20 vs ERC-20 ([BEP-20 vs ERC-20: Features, Use Cases, and Differences - HeLa](https://helalabs.com/blog/bep-20-vs-erc-20-comparative-guide-to-blockchain-token-standards/#:~:text=BEP,unique%20functionalities%20and%20use%20cases)) (confirming that BSC’s BEP-20 token standard aligns with Ethereum’s ERC-20 standard, which is relevant for the smart contract implementation).
