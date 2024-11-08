
# NITS Hackathon
## Deployed Link : https://swanidhi.netlify.app/
## Statement Title
**Micro-Lending Platform Using Blockchain and Web3 Technology in Rural Districts**

### Description
Develop a platform for micro-loans to small businesses and individuals in rural areas, leveraging digital identity verification (e.g., Aadhaar), mobile wallets, and local partnerships. The goal is to build trust through community-based lending models, like Self-Help Groups (SHGs) or peer-to-peer lending, and establish a credit scoring system based on transaction history and repayment patterns. The solution should leverage blockchain to address the financial needs of rural communities.

---

## Key Components of the Solution
The proposed solution may include the following components:

1. **Blockchain-based Digital Identity Verification**  
   Use blockchain technology to securely verify digital identities, such as Aadhaar. This ensures compliance with KYC norms and enables faster, safer user onboarding.

2. **Web3-enabled Mobile Wallet Integration**  
   Facilitate loan disbursement and repayment through Web3-enabled mobile wallets. By leveraging DeFi principles, transactions can occur peer-to-peer, reducing costs and eliminating intermediaries.

3. **Smart Contract-powered Community Lending**  
   Implement smart contracts to enable trustless community-based lending. Self-Help Groups (SHGs) or peer lenders can create contracts that automatically repay funds upon meeting specific conditions, enhancing transparency and accountability.

4. **Blockchain-backed Credit Scoring**  
   Develop a decentralized credit scoring system using blockchain technology. This system would reflect users' transaction history and repayment behavior, ensuring robust and transparent credit scores across financial institutions.

5. **Financial Literacy through Blockchain Education**  
   Provide educational content on blockchain, DeFi, and responsible borrowing. This will empower users to manage their loans effectively and participate confidently in new financial systems.

---

## Tech Stack

### Frontend Team (2 members)
- **Set up the React App**: Create the basic structure and components for the loan application and loan funding forms.
- **Design Loan Request Form**: Implement fields for amount, duration, and loan purpose.
- **Create Loan Funding Display**: Show available loans for lenders to fund, including relevant details.
- **Integrate Web3.js or Ethers.js**: Connect the frontend to the blockchain, allowing users to interact with the smart contract.
- **Implement MetaMask Integration**: Enable wallet connection for authentication and transactions.
- **Finalize UI**: Ensure the application is responsive and functional across devices. Style components using Tailwind CSS or Bootstrap.
- **Deploy the Frontend**: Host on platforms like Vercel or Netlify for easy access and demo.

### Backend Team (2 members)
- **Set up the Backend**: Use Node.js and Express for server-side logic, handling API routes for loan creation and funding.
- **Database Setup**: Implement a simple in-memory database (e.g., SQLite or JSON) to track loan metadata (optional, depending on requirements).
- **Develop API Routes**: Create routes to handle loan requests, funding, and repayment interactions with the frontend.
- **Integrate Blockchain (if needed)**: Set up backend logic to interact with the smart contract for tracking loan statuses and facilitating loan transactions.
- **Ensure Smooth Communication**: Ensure that the backend works seamlessly with the frontend and the blockchain, making sure loans are correctly tracked and processed.
- **Deploy the Backend**: Make the backend accessible to the frontend, supporting core application functionalities.

### Blockchain Developer (1 member)
- **Write the Smart Contract**: Develop a basic Solidity contract for loan creation, disbursement, and repayment with simple interest logic.
- **Deploy on Polygon Mumbai Testnet**: Test the smart contract in a test environment to ensure low-cost, fast transactions.
- **Integrate with Frontend**: Use Web3.js or Ethers.js to enable the frontend to interact with the deployed smart contract.
- **MetaMask Wallet Integration**: Allow users to connect their wallets for authentication and transactions.
- **Test and Debug the Contract**: Ensure that loan requests, funding, and repayments work seamlessly. Fix any issues identified during testing.
- **Ensure Smart Contract Reliability**: Perform final checks to confirm the contract functions as intended, including handling errors and edge cases.
