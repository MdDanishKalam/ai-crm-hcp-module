# ai-crm-hcp-module
# AI-First CRM – HCP Module (Log Interaction System)

## 🚀 Overview

This project is an AI-first CRM system designed for pharmaceutical field representatives to log and manage interactions with Healthcare Professionals (HCPs).

The system enables dual interaction logging:

* Structured Form Input
* Conversational AI Chat Interface

A LangGraph-based AI agent processes inputs and routes them to appropriate tools.

---

## 🧠 Key Features

### 🔹 Dual Input Modes

* Form-based structured logging
* Chat-based natural language logging

### 🔹 AI Agent (LangGraph)

* Intelligent routing of user intent
* Handles interaction workflows dynamically

### 🔹 5 AI Tools Implemented

1. **Log Interaction**
2. **Edit Interaction**
3. **Retrieve Interaction History**
4. **Summarize Interaction**
5. **Suggest Next Action**

### 🔹 LLM Integration

* Designed for Groq (gemma2-9b-it)
* Used for:

  * Entity extraction
  * Summarization
  * Recommendations

---

## ⚙️ Tech Stack

* Frontend: React + Redux
* Backend: FastAPI (Python)
* AI Agent: LangGraph
* LLM: Groq (gemma2-9b-it)
* Database: PostgreSQL (extendable)
* Font: Inter

---

## 🏗️ Project Structure

```
frontend/
backend/
  ├── agents/
  ├── tools/
  ├── services/
  ├── models/
README.md
```

---

## ▶️ How to Run

### Backend

```
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend

```
cd frontend
npm install
npm start
```

---

## 🔄 AI Flow

User Input → LangGraph Agent → Tool Selection → Execution → Structured Output

---

## 🎯 Example Use Case

Input:

```
Met Dr Sharma, discussed diabetes drug, suggest next step
```

Output:

* Extracted HCP data
* Summary generated
* Suggested follow-up action

---

## 💡 Key Differentiator

This system goes beyond CRUD by incorporating:

* AI-driven interaction structuring
* Agent-based decision making
* Real-time recommendations

---

## 📌 Future Enhancements

* Full PostgreSQL integration
* Real-time analytics dashboard
* HCP timeline visualization
* Advanced LLM fine-tuning

---

## 🎥 Demo Video

(Attach your Loom/Drive link here)

---
