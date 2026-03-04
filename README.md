# ⚖️ JustiX – AI-Powered VR Litigation Training Platform

**JustiX** is an immersive, AI-driven litigation training platform. Unlike standard legal AI tools that act as passive *“digital clerks”* for summarization, JustiX provides a **“Trial by Fire”**—allowing law students and professionals to argue cases against an adversarial AI in a high-fidelity **VR courtroom environment**.

---

# The Vision

In the legal world, **a single misplaced word can rewrite a life**. Yet, law students often only get **one Moot Court per semester**.

JustiX changes that.

### Key Capabilities

- **Infinite Litigation**  
  Practice anytime using an **Android-to-VR bridge**.

- **Adversarial Cognition**  
  Face an **AI Opposition** that identifies logical fallacies and cites constitutional law in real-time.

- **Stress Inoculation**  
  Use **VR immersion** to build the *procedural muscle memory* required for high-stakes hearings.

---

# System Architecture

## 1. Dual-RAG Multi-Agent System

The core intelligence of JustiX operates on a **domain-segregated architecture** to ensure deterministic legal reasoning.

### Components

**Isolated Vector Indexes**
- Powered by **Qdrant**
- Uses **OpenAI embeddings** for dense semantic encoding
- Enables high-dimensional ANN search

**Evidentiary Store**
- Case-specific facts and documents uploaded via the **Android App**

**Statutory Knowledge Base**
- Curated index of **constitutional and criminal law**

---

## 2. Adversarial Orchestration Layer

To prevent **LLM hallucinations**, JustiX implements a **constrained reasoning boundary**.

### Agents

**Supervisory Agent**
- Monitors user input and AI responses
- Performs procedural validation
- Ensures citation-backed corrections

**Adversarial Agent**
- Generates counterfactual reasoning
- Grounds arguments strictly in retrieved evidence
- Challenges the user's stance like a real opposing counsel

**Epistemic Isolation**
- Retrieval, orchestration, and evaluation are decoupled into **independent FastAPI-based async microservices**

---

## 3. The “No-Login” VR Sync

Authentication in VR can be frustrating. JustiX solves this with a **Socket.io-based synchronization bridge**.

### Workflow

**Mobile App**
- Upload PDFs and manage cases
- Generate a unique **Meeting ID**

**VR Headset**
- Enter the Meeting ID on a **virtual numpad**
- Instantly sync session data
- Launch the courtroom environment

---

# Tech Stack

| Layer | Technologies |
|------|-------------|
| **VR Client** | Unity, C#, Oculus SDK |
| **Mobile App** | Android (Java/Kotlin), XML |
| **Backend** | FastAPI (Python), Node.js, Socket.io |
| **AI/ML** | Qdrant (Vector DB), OpenAI GPT-4o, LangChain |

---

# The Architects

**Rajan Hasija** – VR Application Development 

**Ruchit Gupta** – AI Architecture & Dual-RAG Orchestration  

**Rudra Gupta** – Backend Systems & Adversarial Logic  

**Pratishtha Takjharia** – VR Platform Designer 

---

# Vision for the Future

JustiX aims to redefine legal education by enabling:

- Continuous courtroom practice
- AI-driven adversarial learning
- Immersive procedural training

**From passive learning → to experiential litigation training.**
