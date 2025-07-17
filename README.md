---

# Blockchain-Based Healthcare Record System

This project demonstrates a **dual blockchain implementation** for secure healthcare data management:

1. **Python Blockchain Simulation** – A custom-built chain to illustrate block creation, Proof-of-Work, tamper detection, and chain validation for medical records.

2. **Ethereum Smart Contract** – A Solidity contract (`PatientRecordContract`) deployed on the **Sepolia testnet** to securely add and transfer patient records between authorised entities.

## 🔧 Features

* SHA-256 cryptographic block hashing
* Genesis block creation and PoW-based block addition
* Chain validation and tampering detection
* Smart contract functions:

  * `addRecord(recordId, recordType)`
  * `transferRecord(toAddress)`
  * `records(recordId)`
  * `totalRecords()`
* Real blockchain deployment with **Remix IDE**, **MetaMask**, and **Etherscan**

##  How to Run

### Python Simulation:

```bash
python blockchain_simulation.py
```

### Smart Contract:

1. Open [Remix IDE](https://remix.ethereum.org)
2. Load `PatientRecordContract.sol`
3. Connect MetaMask (Sepolia Testnet)
4. Deploy and interact via Remix

##  Verified Deployment

Contract deployed to Sepolia:

> [https://sepolia.etherscan.io/address/0x51C6b943892BD9Be3ca1A6468e753D5913Ec3256](https://sepolia.etherscan.io/address/0x51C6b943892BD9Be3ca1A6468e753D5913Ec3256)

##  Limitations

* No role-based access control
* On-chain data not encrypted
* CLI and Remix only (no frontend UI)
* Python simulation is single-node, not decentralised

## Future Improvements

* Add access control (e.g. whitelist for verified providers)
* Use IPFS for encrypted off-chain storage
* Build a React + Web3 UI
* Upgrade Python blockchain to support P2P networking

---

