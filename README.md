# 🦙 LegalLama  
### ⚖️ AI-Powered Legal Assistant with On-Chain Verification  

<p align="center">
  <b>Bridging AI & Blockchain to build Trust in Legal Intelligence</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI-RAG-blue" />
  <img src="https://img.shields.io/badge/Web3-Smart%20Contracts-purple" />
  <img src="https://img.shields.io/badge/Hackathon-Project-green" />
  <img src="https://img.shields.io/badge/Status-Prototype-orange" />
</p>

---

## 🚀 Overview

LegalLama is a **Retrieval-Augmented Generation (RAG)** based AI legal assistant that helps users understand legal case studies, rights, and documents — while validating AI outputs **on-chain** to ensure transparency, integrity, and trust.

Built for a hackathon at the intersection of **AI + Web3 + LegalTech**.

---

## 🎯 Problem Statement

AI-generated legal answers today:

- ❌ Are not verifiable  
- ❌ Can be modified or tampered with  
- ❌ Lack transparency  
- ❌ Provide no authenticity proof  

Users cannot prove whether an AI-generated legal response has been altered.

---

## 💡 Our Solution

LegalLama combines:

- 🧠 Retrieval-Augmented Generation (RAG)  
- 📚 Semantic search over curated legal datasets  
- ⛓ Smart contract-based response validation  

Each AI response is cryptographically hashed and stored on-chain, making it:

- 🔐 Tamper-resistant  
- 🌍 Transparent  
- ✅ Verifiable  

---

## 🏗 System Architecture

```
User
  ↓
Frontend (React / Next.js)
  ↓
Backend API (Node / FastAPI)
  ↓
Vector Database
  ↓
LLM (RAG Model)
  ↓
Smart Contract (Stores Response Hash On-Chain)
```

---

## ⚙️ How It Works

1. 📝 User submits a legal query  
2. 🔎 Backend retrieves relevant legal documents  
3. 🧠 LLM generates a structured legal explanation  
4. ⛓ Response hash is stored on-chain  
5. 📜 User receives AI response + blockchain transaction proof  

---

## ✨ Core Features

- 🔍 Semantic Legal Search  
- 🧠 Retrieval-Augmented Generation  
- ⛓ On-Chain Response Validation  
- 🛡 Tamper-Proof AI Outputs  
- 🧩 Modular API Architecture  
- 💻 Clean, Responsive Frontend  

---

## 🛠 Tech Stack

### 🎨 Frontend
- React / Next.js  
- Tailwind CSS  

### ⚙️ Backend
- Node.js / Express  
or  
- Python / FastAPI  

### 🧠 AI Layer
- Embeddings  
- Vector Database  
- Large Language Model (LLM)  

### ⛓ Blockchain
- Solidity  
- Hardhat  
- EVM-Compatible Network  

---

## 📂 Project Structure

```
legal-llama/
│
├── APIs/              # Backend logic
├── contracts/         # Smart contracts
├── frontend/          # Frontend application
├── .env.example
└── README.md
```

---

## 🔧 Installation & Setup

### 1️⃣ Clone Repository

```
git clone https://github.com/abdulrr25/legal-llama.git
cd legal-llama
```

---

### 2️⃣ Backend Setup

```
cd APIs
npm install
```

Create a `.env` file:

```
PORT=5000
OPENAI_API_KEY=your_api_key
VECTOR_DB_URI=your_vector_db_uri
RPC_URL=your_blockchain_rpc
PRIVATE_KEY=your_wallet_private_key
CONTRACT_ADDRESS=deployed_contract_address
```

Run backend:

```
npm run dev
```

---

### 3️⃣ Smart Contract Deployment

```
cd contracts
npm install
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost
```

Update deployed contract address in backend `.env`.

---

### 4️⃣ Frontend Setup

```
cd frontend
npm install
npm run dev
```

Open in browser:

```
http://localhost:3000
```

---

## 🧪 Example Use Case

**User Query:**  
> What are tenant rights if rent is increased without notice?

### System Response Flow

- Retrieves relevant tenancy laws  
- Generates structured legal explanation  
- Stores response hash on blockchain  
- Returns explanation + transaction proof  

---

## 🏆 Hackathon Value Proposition

LegalLama demonstrates:

- 🔥 Real AI + Web3 integration  
- 🛡 Trust layer for generative AI  
- 🌍 Verifiable AI-generated content  
- ⚖ Practical LegalTech innovation  
- 📈 Scalable modular architecture  

---

## 🔮 Future Improvements

- 🌐 Multi-jurisdiction legal models  
- 👛 Wallet-based authentication  
- 📦 IPFS document storage  
- 📊 AI confidence scoring  
- 🤝 Lawyer consultation marketplace  

---

## ⚠ Disclaimer

LegalLama provides AI-generated legal information for educational purposes only. It does not replace professional legal advice.

---

## 👨‍💻 Author

**Abdul Rahman**  
B.Tech Computer Science  
Full Stack & Web3 Developer  

🔗 GitHub: https://github.com/abdulrr25
