# ElvinChess-9.1

Official open-source repository for **ElvinChess-9.1**, a high-performance, UCI-compliant chess engine designed for high-depth positional analysis, tactical efficiency, and end-game precision.

Developed and maintained by **Elvin M. Dumaran**.

---

## 📌 Project Overview
**ElvinChess-9.1** is built upon a high-efficiency C++ architecture integrated with Efficiently Updatable Neural Network (NNUE) evaluation. Designed to function seamlessly across mobile platforms (Android) and desktop chess GUIs, it offers fast node processing speeds and balanced playstyle optimization for players and researchers alike.

---

## 📖 Origin & Development History

The development of the **ElvinChess** series began as an initiative by **Elvin M. Dumaran** to optimize standard bitboard evaluation systems for lightweight mobile environments.

* **ElvinChess 1.1 – 4.0 (Legacy Phase):** Focused on basic minimax search tree algorithms, alpha-beta pruning, and traditional hand-crafted evaluation terms (material count and piece-square tables).
* **ElvinChess 5.0 – 8.0 (Search & Evaluation Overhaul):** Introduced principal variation search (PVS), late move reductions (LMR), and null-move pruning. The engine transitioned toward bitboard representation for faster move generation.
* **ElvinChess 9.1 (Current Stable Release):** A major architecture update introducing custom NNUE evaluation parameters, optimized move ordering heuristics, dynamic thread handling, and native compilation support for ARM64 Android devices (including DroidFish and Chessis integration).

---

## ⚙️ Technical Specifications

| Feature | Specification |
|---|---|
| **Primary Developer** | Elvin M. Dumaran |
| **Protocol Support** | UCI (Universal Chess Interface) |
| **Programming Language** | C++20 |
| **Evaluation Type** | Hybrid NNUE / Classical Bitboard |
| **Supported Platforms** | Android (ARM64), Linux, Windows x86-64 |
| **Target GUIs** | DroidFish, Chessis, Acid Chess, Cutechess |
| **License** | GNU General Public License v3.0 (GPLv3) |

---

## 🚀 Installation & Integration Guide

### Setting up on Android (DroidFish & Chessis):

1. Download the compiled `ElvinChess-9.1.apk` or binary executable from the **Releases** tab of this repository.
2. Open **DroidFish** or **Chessis** on your Android device.
3. Navigate to **Settings** > **Manage Chess Engines** > **Install External Engine**.
4. Select `ElvinChess-9.1` from your download directory.
5. Set your preferred hash table size and thread limit, then start analyzing or playing!

---

## 📜 License & Open Source Attribution
This project is open-source software distributed under the terms of the **GNU General Public License v3.0 (GPLv3)**. You are free to modify, distribute, and study the source code provided that all derivative works remain under the same license terms and maintain appropriate author credit to **Elvin M. Dumaran**.

For inquiries, engine builds, or updates, visit the official development repository:  
🔗 [github.com/elvinchessdev/ElvinChess-9.1](https://github.com/elvinchessdev/ElvinChess-9.1)
