# Task-3
# 🧠 ICP CRUD DApp - Local Deployment

This is a basic decentralized application (DApp) built on the Internet Computer (ICP) using:

- 🔧 Rust for the backend (canister)
- 💻 React.js for the frontend
- 🧪 CRUD operations (Create, Read, Update, Delete)
- 🌐 Deployed locally using `dfx`

---

## 🚀 Features

- Create, read, update, and delete data on the Internet Computer
- Local deployment with live reloading
- Uses `dfx`, `candid`, and `agent-js`

---

## 🛠️ Requirements

Make sure the following are installed:

- [Rust](https://www.rust-lang.org/)
- [Node.js](https://nodejs.org/)
- [dfx SDK](https://internetcomputer.org/docs/current/developer-docs/setup/install/install-dfx)

---

## ⚙️ How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/your-username/icp-crud-dapp.git
cd icp-crud-dapp

# 2. Start the ICP local replica
dfx start --background

# 3. Deploy the canisters
dfx deploy

# 4. Run frontend (if not already set to auto-launch)
npm install
npm start
