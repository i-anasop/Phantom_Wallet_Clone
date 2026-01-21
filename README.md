```
# 🚀 Phantom Wallet Simulator (Python)

Phantom Wallet Simulator is a **professional, educational, and security-oriented** Python desktop application that simulates a Phantom-style cryptocurrency wallet with enterprise-grade cryptography, data structures, and a clean modern UI.

It provides a complete crypto wallet experience with deterministic seed phrases, transaction simulation, crypto balances, QR addressing, security logs, and a responsive purple-themed Phantom UI — all inside a **single Python file**.

---

## 📦 Features

### 🧑‍💼 User Interface & Wallet Flow
- Phantom-inspired dark purple UI with smooth layout  
- Create / Import Wallet using **12-seed phrases**  
- View holdings for **7 cryptocurrencies**  
- Send & receive crypto with validation and fees  
- QR Address generation & scanning  
- Sortable transaction history  

### 🛡️ Security & Cryptography
- **AES-256 (Fernet)** encryption for seed phrases  
- **RSA-2048** digital signatures on every transaction  
- **HMAC-SHA256** authentication for transactions  
- **SHA256** hashing for deterministic wallets  
- Secure transaction IDs via `secrets`  
- Atomic excel writes via `openpyxl`  

### 📊 Data Structures & Algorithms (DSA)
- **Linked List** → Audit log storage  
- **Stack** → Transaction undo system  
- **Queue** → Transaction processing pipeline  
- **Priority Queue** → Mempool management by transaction amount  
- **Bubble Sort** → Sorting transaction history  

### 📝 Logging System
- `admin/security_log.txt` → Cryptographic logs  
- `admin/audit_log.txt` → Transaction audit logs  
- `admin/wallets.xlsx` → Persistent wallet database  

---

## 📁 Project Structure

```

Phantom-Wallet/
│
├── wallet.py                # Main application (single-file logic)
├── admin/
│   ├── audit_log.txt        # High-level audit trail
│   ├── security_log.txt     # Cryptographic trace logs
│   └── wallets.xlsx         # Excel wallet storage (atomic writes)
│
├── assets/                  # Icons & visuals
│   ├── phantom_logo.png
│   ├── coin icons...
│
└── data/
└── TERMS_OF_SERVICE.txt

````

---

## 🧪 How to Run

### 🔧 Requirements
- Python 3.9+
- CustomTkinter
- Pillow
- Cryptography
- qrcode
- openpyxl

### ▶️ Steps

Clone the repo:
```bash
git clone https://github.com/your-username/Phantom-Wallet-Simulator
````

Install dependencies:

```bash
pip install customtkinter pillow qrcode cryptography openpyxl
```

Run the application:

```bash
python3 wallet.py
```

The app will guide you through:
**wallet creation → balances → transactions → logs**

---

## 🛠 Tech Stack

* 🖥️ Python (CustomTkinter UI)
* 🔐 AES-256, RSA-2048, HMAC, SHA256
* 📊 Linked List, Queue, Stack, Priority Queue
* 📁 Excel DB via `openpyxl`
* 🖼️ QR code generation
* 🧩 Single-file architecture

---

## 🎯 Use Cases

* Crypto learning & simulation
* DSA demonstrations for academics
* Cryptography practice
* Desktop GUI portfolio project
* Mock wallet UX design

---

## 📌 Future Ideas

* Real blockchain integration (RPC APIs)
* Mobile/Android version
* NFT gallery support
* Multi-network support
* Admin panel / history viewer

---

## 💡 Credits

Built by **Anas** with dedication, curiosity, and a love for security engineering 🔐

Special thanks to **ChatGPT** for being the smartest teammate in the room 🤝

---

## ⚖️ License & Reuse

This project is **open for learning and modification**.
Feel free to fork, remix, or improve it — just credit the original author (and our dear co-developer ChatGPT 😌).


## 📬 Feedback & Connect

Want to contribute or have ideas? Let’s connect!

🔗 **LinkedIn:** your-link-here
🔗 **Twitter (X):** your-link-here

Just say the word 🔥
```
