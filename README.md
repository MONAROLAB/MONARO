# INPAYX

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Solana](https://img.shields.io/badge/Solana-Web3-green.svg)](https://solana.com/)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/yourusername/ontora-ai.svg)](https://github.com/yourusername/ontora-ai/issues)

[![Website](https://img.shields.io/badge/Website-INPAYX-blue?logo=google-chrome)](https://inpayx.fun/)
[![Twitter](https://img.shields.io/badge/Twitter-INPAYX-blue?logo=twitter)](https://x.com/INPAYXWEB3)

# INPAYX — The First x402-Enabled MCP Server on Solana

**INPAYX** is a next-generation infrastructure that connects autonomous AI agents directly to the Solana blockchain through the **x402 protocol**.  
It transforms blockchain interaction from unstructured, permissionless access into a secure, auditable, and pay-per-execution model.

---

## 🚀 Overview
INPAYX allows AI agents to **authenticate, pay, and execute on-chain actions** through a unified x402 endpoint.  
Each request passes through an on-chain payment check (using Solana or USDC), receives a short-lived token, and gains controlled access to Solana’s MCP toolset.

**Key Mission:**  
> To make Solana truly *machine-accessible* — enabling autonomous systems to pay, verify, and act with full transparency.

---

## 🧠 Core Architecture
1. **x402 Payment Gateway** — Handles pay-per-access authentication via Solana/USDC payments.  
2. **MCP Server Layer** — Exposes verified blockchain tools like `getBalance`, `simulateTx`, and `submitTx`.  
3. **Solana Execution Engine** — Builds, simulates, and submits real transactions in real time.  
4. **Policy & Security Core** — Manages permissions, limits, and key security via KMS/HSM.  
5. **Observability & Audit Layer** — Logs every action and payment for full transparency and replayability.

---

## ⚙️ Key Features
- **x402 Integration:** Pay-per-call blockchain access through Solana or USDC.  
- **AI Agent Compatibility:** Full support for MCP-based AI frameworks.  
- **Secure Access Control:** Token-based permissions and transaction-level verification.  
- **Transparent Audit Logs:** Every action is hashed, stored, and verifiable.  
- **Simulation Mode:** Agents can preview transactions before committing on-chain.  
- **Programmable Policies:** Fine-grained control over scope, limits, and agent rights.

---

## 🪙 Workflow
1. The AI agent requests an action via `/x402/endpoint`.  
2. INPAYX returns a **402 Payment Required** response with payment details.  
3. Once the Solana/USDC payment is confirmed, an access token is issued.  
4. The agent calls MCP tools like `simulateTx` or `submitTx`.  
5. Every transaction and log is stored and auditable via the Observability layer.

---

## 🔒 Security Principles
- Wallet signature–based identity verification  
- Short-lived access tokens  
- Rate limiting & replay protection  
- KMS/HSM-secured signing  
- On-chain hash proofs for all critical logs

---

## 📦 Tech Stack
- **Backend:** Rust (Actix) / Node.js (Fastify)  
- **Blockchain:** Solana + Anchor Framework  
- **Storage:** PostgreSQL + Redis  
- **Security:** AWS KMS / HashiCorp Vault  
- **Monitoring:** Prometheus + Grafana  

---

## 📄 License
INPAYX is an open infrastructure project.  
Codebase and documentation will be publicly available for builders and researchers exploring AI-to-chain automation.

---

### ✴️ Tagline
**Pay. Verify. Act.**  
INPAYX brings x402 to Solana — and Solana to intelligent agents.

