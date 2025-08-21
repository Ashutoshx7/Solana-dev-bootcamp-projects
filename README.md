# Solana Developer Bootcamp Projects (2025)

This repository contains all **13 projects** I completed during the **Solana Developer Bootcamp 2024**.  
These projects demonstrate **Rust + Anchor programming**, **on-chain logic**, **DeFi concepts**, **NFTs**, **security testing**, and **production deployment**.

---

## 📌 Quick Overview
- **Language / Framework:** Rust, Anchor  
- **Client:** TypeScript  
- **Solana concepts:** SVM runtime, PDAs, CPIs, SPL tokens, NFTs  
- **Extra tools:** RPC indexing, Geyser plugins, Solana CLI  

---

## 📂 Projects at a Glance

### **Core Programs**
1. **Favorites Program** – Store and update user favorites on-chain  
2. **Voting App** – PDAs, instructions, account management  
3. **Blinks & Actions Integration** – Off-chain + on-chain interactions  
4. **CRUD App** – Create/Read/Update/Delete operations in Solana programs  

### **Token / NFT / DeFi**
5. **Token Creation** – SPL token minting and transfers  
6. **NFT Minting** – Metadata, minting flow, NFT ownership  
7. **Swap Program** – Token-to-token swap logic  
8. **Token Vesting App** – Time-locked token releases  
9. **Token Lottery** – Randomized lottery selection  

### **Advanced / Security / Production**
10. **Lending Application** – Borrowing & lending implementation  
11. **Programmable Money** – Conditional transfers  
12. **Attacking the Bank** – Finding and exploiting program vulnerabilities  
13. **Getting to Production** – Mainnet deployment best practices  

---

## 🚀 Running Any Project
All projects are in separate folders with individual READMEs.  
General workflow:  
```bash
# Start a local validator
solana-test-validator

# Go into a specific project folder
cd project-01-favorites

# Build and deploy program
anchor build
anchor deploy

# Run the test suite
anchor test
