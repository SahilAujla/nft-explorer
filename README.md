# NFT Explorer

## Overview

This project contains a fully fledged Next.js based NFT Explorer capable of fetching nfts by:
- Collections
- External and connected wallet

Across all EVM compatible chains.

I've used [Create Web3 Dapp](https://github.com/alchemyplatform/create-web3-dapp) to create it!

## Supported Chains

The project supports all the major EVM chains:

 - Ethereum
 - Polygon
 - Arbitrum
 - Optimism


## Getting Started

### Prerequisites

To get started with this boilerplate, you'll need to have the following software installed on your local machine:

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)


### Running the Project

1. Inside the project folder, start the local development server:
   ```
   yarn run dev
   ```
2. Open your browser and navigate to [`http://localhost:3000/`](http://localhost:3000/) to view the dApp in action.


## Project Structure

```
📦root
 ┣ 📂components
 ┃ ┣ 📂navigation
 ┃ ┃ ┗ 📜navbar.jsx
 ┃ ┗ 📜nftGallery.jsx
 ┣ 📂layout
 ┃ ┗ 📜mainLayout.jsx
 ┣ 📂pages
 ┃ ┣ 📂api
 ┃ ┃ ┣ 📜getNftsForCollection.js
 ┃ ┃ ┗ 📜getNftsForOwner.js
 ┃ ┣ 📜_app.js
 ┃ ┗ 📜index.jsx
 ┣ 📂public
 ┃ ┗ 📜alchemy_logo.svg
 ┣ 📂styles
 ┃ ┣ 📜Home.module.css
 ┃ ┣ 📜Navbar.module.css
 ┃ ┣ 📜NftGallery.module.css
 ┃ ┗ 📜globals.css
 ┣ 📜.env.local
 ┣ 📜.gitignore
 ┣ 📜README.md
 ┣ 📜package-lock.json
 ┗ 📜package.json
```
