# 🏆 Limited Time Auction - Solidity Smart Contract  

## 📜 Project Description  
The **Limited Time Auction** smart contract allows users to bid for an item within a fixed time period. The highest bidder at the end of the auction wins, and only the owner can withdraw the funds after the auction closes.  

## 🚀 Features  
- **Automated Auction Closing**: The auction automatically closes after a fixed time (e.g., 1 hour).  
- **No Input Needed at Deployment**: The auction starts as soon as the contract is deployed.  
- **Secure Bidding**: Only higher bids are accepted, and the previous highest bidder gets refunded.  
- **Withdrawal Function**: Users can withdraw their refunded bids.  
- **Owner Controls Funds**: Only the contract owner can withdraw the final bid amount.  

## 📍 Deployed Address  
🔹 **Deployed on Edu Chain**  
🔹 **Contract Address:** `YOUR_DEPLOYED_ADDRESS_HERE`  

## 📂 How to Use  
1. **Deploy the Contract** (Already deployed at the above address).  
2. **Users Bid** by sending ETH using the `bid()` function.  
3. **Auction Ends Automatically** after 1 hour.  
4. **Withdraw Bids** using `withdraw()` if outbid.  
5. **Finalize Auction** using `finalizeAuction()`.  
6. **Owner Withdraws Funds** using `ownerWithdraw()`.  

## ⚡ Show this to  
- Anyone who wants to participate in the auction.  
- Developers learning Solidity and smart contract development.  
- Blockchain enthusiasts looking for **automated auction mechanisms**.  

## 📜 License  
This project is licensed under the **MIT License**.  
