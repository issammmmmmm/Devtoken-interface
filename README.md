# Project 2 – DevToken Web Interface (ERC-20)

A simple web interface built with **React (Vite)** and **Ethers.js**, allowing users to interact with the ERC-20 `DevToken` smart contract deployed on the **Polygon Amoy testnet**.

---

## 🔗 Smart Contract

- **Contract Name**: DevToken  
- **Contract Address**: `0xdAcdF09E174Ee1a99b3EF447dFdb6CE9dB4B1B21`  
- **View on Polygonscan**: [Polygonscan Link](https://amoy.polygonscan.com/address/0xdAcdF09E174Ee1a99b3EF447dFdb6CE9dB4B1B21)

---

## 🎯 Features

- 🔌 Connects to **MetaMask**
- 🧾 Reads wallet balance using `balanceOf(address)`
- 📤 Transfers tokens using `transfer(address, amount)`
- 🔄 Refresh button for real-time balance update
- 📡 Powered by **Ethers.js** and **Vite**

---

## 🧱 Project Structure

- `App.jsx`: React component with wallet connection, balance reader, and token transfer logic
- `src/abi/devtoken.js`: ABI of the DevToken smart contract
- `contracts/devtoken.sol`: Solidity contract (same as used in Day 1)
- `video-demo.mp4`: Demo of the working interface

---

## 🎥 Demo Video

📺 Find the **demo video** inside the repository.  
It shows:

- Launching the local interface with `npm run dev`
- Connecting MetaMask
- Viewing balance
- Sending `10 DVT` tokens
- Confirming transaction in MetaMask
- Verifying on **Polygonscan**

---

## 🧪 Status

✅ **Working** – Fully functional on **Polygon Amoy testnet**

---

## 🛠️ Tech Stack

- **Frontend**: React (Vite)
- **Blockchain Interaction**: Ethers.js
- **Wallet**: MetaMask
- **Smart Contract**: Solidity (ERC-20 via OpenZeppelin)

---

## 📁 Files in this Repo

- `devtoken.sol`: The smart contract (for reference)
- `App.jsx`: Main frontend logic
- `devtoken.js`: ABI used in frontend
- `video-demo.mp4`: Complete working demonstration

---

