# Share
🌐 Google Clarity Web3 Procurement Smart Contract

This project contains a **Clarity smart contract** that demonstrates how a global company (like Google) could use **Web3 technology** to run **transparent procurement processes** on the Stacks blockchain.  

It allows project owners to post opportunities, vendors to submit bids, evaluators to score them, and the system to automatically determine the winner using a **quality-cost balance formula**.  

✨ Features

- **Project Creation**
  - Owners can publish procurement opportunities with budget and deadlines.  

- **Vendor Bidding**
  - Vendors submit cost proposals with a reference to off-chain documents (IPFS/Arweave).  

- **Scoring**
  - Evaluators assign quality/performance scores to bids.  

- **Winner Selection**
  - The contract determines the winning vendor using:  
    ```
    weighted-score = (quality-score * 1000) / cost
    ```
  - Ensures a balance between low cost and high quality.  

- **Transparency**
  - All bids, scores, and results are immutably stored on-chain.  

🚀 Getting Started


