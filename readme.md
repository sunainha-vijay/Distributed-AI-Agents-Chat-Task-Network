# 🧠 NANDA Mini Project — Internet of AI Agents

A simple, hands-on project that demonstrates the **core principles of NANDA (Networked Autonomous Neural Distributed Agents)** architecture using Python.  
This mini project builds a **lightweight multi-agent system** where autonomous agents communicate over a protocol, collaborate to solve simple tasks, and emulate a decentralized intelligence network.

---

## ✨ Features

- 🕸️ **Peer-to-peer agent communication** over WebSockets  
- 🤖 Multiple autonomous agents (MathBot, InfoBot, Client)  
- 🧠 Lightweight task routing and distributed problem solving  
- 🔐 Structured JSON messaging protocol  
- 🧩 Extensible to more complex agent behaviors

---

## 🏗️ Architecture Overview

- **Coordinator:** WebSocket hub that connects agents and forwards messages.  
- **MathBot:** Solves math expressions.  
- **InfoBot:** Responds with simple facts.  
- **Client:** Sends tasks and receives responses.

---

## 🧰 Tech Stack

- **Language:** Python 3.8+  
- **Libraries:**  
  - `asyncio` — for async execution  
  - `websockets` — for communication  
  - `json` — for structured message exchange

---

## ⚡ Installation & Setup

git clone https://github.com/your-username/nanda-mini.git
cd nanda-mini

python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows

pip install websockets


