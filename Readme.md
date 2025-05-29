# 🕹️ Tic-Tac-Toe On-Chain

## 📜 Project Description

This project is a decentralized, on-chain implementation of the classic **Tic-Tac-Toe** game, built using the Clarity smart contract language and deployed on the **Stacks Testnet**. The smart contract enables two players to wager STX tokens and compete in a fully trustless and transparent environment, where every move, bet, and outcome is verifiable on the blockchain.

The contract handles game creation, joining, move validation, winner determination, and bet payouts — all without any centralized server.

---

## 🔭 Project Vision

The vision behind this project is to **demonstrate the capabilities of decentralized gaming** on the Stacks blockchain. By building a game with real value transactions and deterministic rules, we aim to:

* Showcase the potential of Clarity smart contracts for interactive applications.
* Encourage developers and gamers to explore on-chain game mechanics.
* Establish a foundation for more advanced and competitive blockchain-based gaming experiences.

---

## ⭐ Key Features

* ✅ **Create New Game:** A player can initiate a game with an STX bet and an opening move.
* 🔄 **Join Existing Game:** A second player can join by matching the bet and making a move.
* 🎮 **Play Turns:** Alternating moves are made in turn by each player, enforced by the smart contract.
* 🧠 **Move Validation:** Ensures valid index, move type (X or O), and non-overlapping cell updates.
* 🏆 **Winner Detection:** Automatically detects winning combinations and declares the winner.
* 💰 **Bet Handling:** Secure STX transfer and winner reward handled directly by the contract.
* 🔐 **On-chain Logic:** Entire game logic (board state, turn tracking, and result handling) is stored and computed on-chain.

---

## 🚀 Future Scope

* 🧩 **Game UI Integration:** Build a front-end interface (e.g., React + Stacks.js) for users to play the game easily.
* 💬 **Move History & Chat:** Add metadata or logging features to track past moves and enable player interactions.
* 🪙 **NFT Rewards:** Mint NFTs as proof of victory or participation using the Clarity NFT standards (SIP-009).
* 👾 **Game Modes:** Introduce more game types (e.g., 4x4 boards, tournament brackets).
* 🧪 **Unit Testing & Auditing:** Add test coverage and run audits for security and consistency.
* 🌍 **Multiplayer Lobby System:** Allow multiple games and players to interact via a smart contract lobby mechanism.
