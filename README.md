<div align="center" ><img width="350px" src="https://github.com/eben619/Zero-To-Dapp-Workshop/blob/main/universityOfGhana.svg"></div>

<h1>Introduction to Ethereum Development: Key Terms and Concepts</h1>

<p>Welcome to the world of Ethereum development! This guide will introduce you to the essential terms and concepts you need to know as a beginner blockchain developer. By the end of this guide, you’ll have a solid understanding of blockchain fundamentals and Ethereum-specific concepts.</p>

<hr />

<h2>What is Blockchain?</h2>

<details>
<summary><strong>Definition</strong></summary>
<p>A blockchain is a decentralized, distributed ledger that records transactions across a network of computers. Each block contains a list of transactions, and these blocks are linked together in a chain, hence the name "blockchain."</p>
</details>

<details>
<summary><strong>Key Features</strong></summary>
<ul>
  <li><strong>Decentralization</strong>: No single entity controls the network.</li>
  <li><strong>Transparency</strong>: All transactions are visible to everyone on the network.</li>
  <li><strong>Immutability</strong>: Once data is recorded, it cannot be altered.</li>
</ul>
</details>

<hr />

<h2>What is Ethereum?</h2>

<details>
<summary><strong>Definition</strong></summary>
<p>Ethereum is a decentralized, open-source blockchain platform that enables developers to build and deploy smart contracts and decentralized applications (dApps). Unlike Bitcoin, which is primarily a digital currency, Ethereum is a programmable blockchain.</p>
</details>

<details>
<summary><strong>Key Features</strong></summary>
<ul>
  <li><strong>Smart Contracts</strong>: Self-executing contracts with the terms of the agreement written in code.</li>
  <li><strong>Ether (ETH)</strong>: The native cryptocurrency of the Ethereum network, used to pay for transactions and computational services.</li>
  <li><strong>Decentralized Applications (dApps)</strong>: Applications that run on the Ethereum blockchain.</li>
</ul>
</details>

<hr />

<h2>Key Blockchain Terms</h2>

<details>
<summary><strong>Node</strong></summary>
<p>A computer that participates in the blockchain network by validating and relaying transactions. Nodes maintain a copy of the blockchain and ensure its integrity.</p>
</details>

<details>
<summary><strong>Consensus Mechanism</strong></summary>
<p>A method used to achieve agreement on the state of the blockchain across all nodes. Common consensus mechanisms include Proof of Work (PoW) and Proof of Stake (PoS).</p>
</details>

<details>
<summary><strong>Gas</strong></summary>
<p>A unit of measurement for the computational effort required to execute operations on the Ethereum network. Gas fees are paid in Ether (ETH) and compensate miners (or validators) for their work.</p>
</details>

<details>
<summary><strong>Wallet</strong></summary>
<p>A software application that allows users to interact with the blockchain. Wallets store private keys, which are used to sign transactions and prove ownership of assets.</p>
</details>

<hr />

<h2>Consensus Mechanisms</h2>

<details>
<summary><strong>Proof of Work (PoW)</strong></summary>
<p>PoW is a consensus mechanism where miners solve complex mathematical puzzles to validate transactions and create new blocks. The first miner to solve the puzzle gets to add the block to the blockchain and is rewarded with cryptocurrency.</p>

<h4>Pros:</h4>
<ul>
  <li>High security due to computational difficulty.</li>
</ul>

<h4>Cons:</h4>
<ul>
  <li>Energy-intensive and environmentally unfriendly.</li>
</ul>
</details>

<details>
<summary><strong>Proof of Stake (PoS)</strong></summary>
<p>PoS is a consensus mechanism where validators are chosen to create new blocks based on the number of tokens they hold and are willing to "stake" as collateral. Validators are rewarded with transaction fees.</p>

<h4>Pros:</h4>
<ul>
  <li>Energy-efficient compared to PoW.</li>
</ul>

<h4>Cons:</h4>
<ul>
  <li>Wealth concentration can lead to centralization.</li>
</ul>
</details>

<details>
<summary><strong>Delegated Proof of Stake (DPoS)</strong></summary>
<p>DPoS is a variation of PoS where token holders vote for a small number of delegates to validate transactions and create blocks on their behalf.</p>

<h4>Pros:</h4>
<ul>
  <li>Faster transaction processing.</li>
</ul>

<h4>Cons:</h4>
<ul>
  <li>Potential for centralization if delegates collude.</li>
</ul>
</details>

<hr />

<h2>Smart Contracts</h2>

<details>
<summary><strong>Definition</strong></summary>
<p>Smart contracts are self-executing contracts with the terms of the agreement directly written into code. They automatically execute and enforce the terms when predefined conditions are met.</p>
</details>

<details>
<summary><strong>Use Cases</strong></summary>
<ul>
  <li>Decentralized Finance (DeFi): Lending, borrowing, and trading without intermediaries.</li>
  <li>Supply Chain Management: Tracking goods and ensuring transparency.</li>
  <li>Digital Identity: Verifying identity without centralized authorities.</li>
</ul>
</details>

<hr />

<h2>Decentralized Applications (dApps)</h2>

<details>
<summary><strong>Definition</strong></summary>
<p>dApps are applications that run on a blockchain network rather than a centralized server. They leverage smart contracts for their backend logic and often have a frontend user interface.</p>
</details>

<details>
<summary><strong>Examples</strong></summary>
<ul>
  <li><strong>Uniswap</strong>: A decentralized exchange for trading tokens.</li>
  <li><strong>CryptoKitties</strong>: A game where users can collect and breed digital cats.</li>
  <li><strong>Compound</strong>: A DeFi platform for lending and borrowing cryptocurrencies.</li>
</ul>
</details>

<hr />


<h2>Final Thoughts</h2>

<p>Blockchain and Ethereum development are exciting fields with endless possibilities. By understanding these key terms and concepts, you’re well on your way to becoming a proficient blockchain developer. Keep learning, experimenting, and building! 🚀</p>
<h1>Campus Tour Workshop: Deploy Your Own Tokens</h1>

<p>Welcome to our <strong> Educational Workshop</strong>! Over the next two days, you’ll learn how to create and deploy your own ERC-20 (fungible) and ERC-721 (non-fungible) tokens on the Ethereum blockchain. No prior experience is required—just bring your curiosity and enthusiasm!</p>

<hr />

<h2> Deploying Your Own ERC-20 Token</h2>

<details>
<summary><strong>What is an ERC-20 Token?</strong></summary>
<p>ERC-20 is a standard for fungible tokens on the Ethereum blockchain. Fungible tokens are interchangeable, like currencies (e.g., 1 ETH = 1 ETH).</p>

<h4>Key Features of ERC-20 Tokens:</h4>
<ul>
  <li><strong>Total Supply</strong>: The total number of tokens in circulation.</li>
  <li><strong>Balance</strong>: The number of tokens held by an address.</li>
  <li><strong>Transfer</strong>: Sending tokens from one address to another.</li>
  <li><strong>Approve and TransferFrom</strong>: Allowing third parties to transfer tokens on your behalf.</li>
</ul>
</details>

<details>
<summary><strong>Step 1: Set Up Your Environment</strong></summary>
<ol>
  <li>Open <a href="https://remix.ethereum.org/" target="_blank">Remix IDE</a>, a browser-based Solidity IDE.</li>
  <li>Connect your <a href="https://metamask.io/" target="_blank">MetaMask</a> wallet to Remix.</li>
  <li>Ensure MetaMask is connected to a testnet like Ropsten or Rinkeby.</li>
</ol>
</details>

<details>
<summary><strong>Step 2: Write the ERC-20 Contract</strong></summary>
<p>Here’s a simple ERC-20 token contract using OpenZeppelin’s library:</p>

<pre><code>// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MyToken is ERC20 {
    constructor(uint256 initialSupply) ERC20("MyToken", "MTK") {
        _mint(msg.sender, initialSupply);
    }
}</code></pre>

<h4>Explanation:</h4>
<ul>
  <li><strong><code>ERC20("MyToken", "MTK")</code></strong>: Creates a token with the name "MyToken" and symbol "MTK".</li>
  <li><strong><code>_mint(msg.sender, initialSupply)</code></strong>: Mints the initial supply of tokens to the deployer's address.</li>
</ul>
</details>

<details>
<summary><strong>Step 3: Compile and Deploy</strong></summary>
<ol>
  <li>Compile the contract in Remix.</li>
  <li>Deploy the contract to the testnet using MetaMask.</li>
  <li>Confirm the transaction in MetaMask.</li>
</ol>
</details>

<details>
<summary><strong>Step 4: Interact with Your ERC-20 Token</strong></summary>
<ol>
  <li><strong>Check Your Balance</strong>: Use the <code>balanceOf</code> function in Remix to check your token balance.</li>
  <li><strong>Transfer Tokens</strong>: Use the <code>transfer</code> function to send tokens to another address.</li>
  <li><strong>Approve and TransferFrom</strong>: Use <code>approve</code> to allow another address to spend your tokens, then use <code>transferFrom</code> to transfer tokens on their behalf.</li>
</ol>
</details>

<hr />

<h2> Deploying Your Own ERC-721 Token</h2>

<details>
<summary><strong>What is an ERC-721 Token?</strong></summary>
<p>ERC-721 is a standard for non-fungible tokens (NFTs) on the Ethereum blockchain. NFTs are unique and indivisible, like collectibles or digital art.</p>

<h4>Key Features of ERC-721 Tokens:</h4>
<ul>
  <li><strong>Token ID</strong>: A unique identifier for each token.</li>
  <li><strong>Owner</strong>: The address that owns a specific token.</li>
  <li><strong>Metadata</strong>: Additional information about the token (e.g., image, description).</li>
</ul>
</details>

<details>
<summary><strong>Step 1: Set Up Your Environment</strong></summary>
<ol>
  <li>Open <a href="https://remix.ethereum.org/" target="_blank">Remix IDE</a>.</li>
  <li>Connect your <a href="https://metamask.io/" target="_blank">MetaMask</a> wallet to Remix.</li>
  <li>Ensure MetaMask is connected to a testnet like Ropsten or Rinkeby.</li>
</ol>
</details>

<details>
<summary><strong>Step 2: Write the ERC-721 Contract</strong></summary>
<p>Here’s a simple ERC-721 token contract using OpenZeppelin’s library:</p>

<pre><code>// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC721/ERC721.sol";
import "@openzeppelin/contracts/utils/Counters.sol";

contract MyNFT is ERC721 {
    using Counters for Counters.Counter;
    Counters.Counter private _tokenIds;

    constructor() ERC721("MyNFT", "MNFT") {}

    function mintNFT(address recipient, string memory tokenURI) public returns (uint256) {
        _tokenIds.increment();
        uint256 newItemId = _tokenIds.current();
        _mint(recipient, newItemId);
        _setTokenURI(newItemId, tokenURI);
        return newItemId;
    }
}</code></pre>

<h4>Explanation:</h4>
<ul>
  <li><strong><code>ERC721("MyNFT", "MNFT")</code></strong>: Creates an NFT collection with the name "MyNFT" and symbol "MNFT".</li>
  <li><strong><code>mintNFT</code></strong>: Mints a new NFT and assigns it to the recipient with a unique token ID and metadata URI.</li>
</ul>
</details>

<details>
<summary><strong>Step 3: Compile and Deploy</strong></summary>
<ol>
  <li>Compile the contract in Remix.</li>
  <li>Deploy the contract to the testnet using MetaMask.</li>
  <li>Confirm the transaction in MetaMask.</li>
</ol>
</details>

<details>
<summary><strong>Step 4: Interact with Your ERC-721 Token</strong></summary>
<ol>
  <li><strong>Mint Your First NFT</strong>: Call the <code>mintNFT</code> function with your address and a metadata URI (e.g., an IPFS link).</li>
  <li><strong>Check Ownership</strong>: Use the <code>ownerOf</code> function in Remix to check who owns a specific token.</li>
  <li><strong>Transfer NFTs</strong>: Use the <code>transferFrom</code> function to send an NFT to another address.</li>
</ol>
</details>

<hr />

<h2>Additional Resources</h2>

<h3>Tools:</h3>
<ul>
  <li><a href="https://remix.ethereum.org/" target="_blank">Remix IDE</a>: A browser-based Solidity IDE.</li>
  <li><a href="https://metamask.io/" target="_blank">MetaMask</a>: A crypto wallet for interacting with Ethereum.</li>
  <li><a href="https://openzeppelin.com/" target="_blank">OpenZeppelin</a>: A library for secure smart contract development.</li>
</ul>

<h3>Documentation:</h3>
<ul>
  <li><a href="https://soliditylang.org/" target="_blank">Solidity Documentation</a>.</li>
  <li><a href="https://docs.openzeppelin.com/contracts/4.x/erc20" target="_blank">OpenZeppelin ERC-20 Documentation</a>.</li>
  <li><a href="https://docs.openzeppelin.com/contracts/4.x/erc721" target="_blank">OpenZeppelin ERC-721 Documentation</a>.</li>
</ul>

<hr />

<h2>Final Thoughts</h2>

<p>By the end of this two-day workshop, you’ll have deployed your own ERC-20 and ERC-721 tokens and gained hands-on experience with Ethereum development. Keep experimenting, and happy coding! 🚀</p>
