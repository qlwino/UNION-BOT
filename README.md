
# 🤖 Union Auto TX Bot

A lightweight automated bot for interacting with the Union protocol on Sepolia testnet. Designed for quick transaction batching, USDC approvals, and seamless routing to Babylon or Holesky destinations.

---

## ⚙️ Features

- 🔁 **Auto Transaction Execution**
  - Perform multiple token sends per wallet in a single run
- ✅ **USDC Approval Handling**
  - Automatically approves token spending if not already approved
- 📡 **Destination Selection**
  - Choose between Babylon, Holesky, or let the bot pick randomly
- 🛡 **Input Validation**
  - Prevents malformed keys or unsupported wallet formats
- 🧪 **Testnet Support**
  - Fully operational with Sepolia testnet and associated chains

---

## 📦 Setup

### 1. Clone the Repository
```bash
https://github.com/qlwino/UnionTestnet-BOT.git
cd UnionTestnet-BOT
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory with the following format:

```ini
PRIVATE_KEY_1=0xabc...
BABYLON_ADDRESS_1=bbn1...

PRIVATE_KEY_2=0xdef...
BABYLON_ADDRESS_2=bbn1...
```

You can add as many wallets as you want by following the pattern.

---

## 🚀 Usage

```bash
node index.js
```

You’ll be prompted to:


* Choose the transaction destination (Babylon, Holesky, or Random)
* Specify how many transactions per wallet

---

## 📋 Example Output

```
[?] Masukkan kata sandi untuk memulai skrip (kata sandi akan terlihat): 
[✅] Kata sandi benar. Memulai skrip...
[➤] Wallet1 | Transaksi 1/5
[✅] Transaksi Dikonfirmasi: https://sepolia.etherscan.io/tx/0x...
```

---

## 🧑‍💻 Author

Script maintained by **m9lwen**

---

## 📄 License

MIT — For educational/testnet use only.
