
---

# Blockchain Healthcare Record System

A lightweight project that uses **Python** and **Solidity** to simulate secure healthcare data storage with blockchain technology.

## Key Components

* **Python Blockchain**: Simulates block creation, Proof-of-Work, and tamper detection.
* **Solidity Smart Contract**: Deployed on Sepolia Testnet to manage patient records.

## Features

* SHA-256 hashing
* Genesis block + PoW
* Smart contract: `addRecord`, `transferRecord`, `records`, `totalRecords`
* MetaMask + Remix IDE + Etherscan integration

## How to Run

**Python Blockchain**

```bash
python blockchain_simulation.py
```

**Solidity Contract**

1. Open [Remix IDE](https://remix.ethereum.org)
2. Load `PatientRecordContract.sol`
3. Connect MetaMask (Sepolia)
4. Deploy & test

## Demo Contract

 [Sepolia Etherscan](https://sepolia.etherscan.io/address/0x51C6b943892BD9Be3ca1A6468e753D5913Ec3256)

## Limitations

* No access control
* No UI
* No encryption
* Local-only simulation

## Future Plans

* Add role-based access
* Off-chain storage (IPFS)
* React/Web3 frontend
* Multi-node blockchain

---


