# 🧠 MindMentor

> A multi-agent AI mentor blending philosophical frameworks and psychological wisdom for clarity, reflection, and personal growth.

---

## 📖 Overview

**MindMentor** is an intelligent self-reflection and mentorship platform designed to help users navigate complex personal, professional, and emotional challenges. Rather than providing generic chatbot responses or clinical diagnostic advice, MindMentor acts as a philosophical guide—drawing from frameworks like **Stoicism**, **Cognitive Reframing**, and **Jungian psychology** to foster clarity and resilience.

Built on an event-driven multi-agent architecture, the system coordinates specialized agents to listen actively, research relevant philosophical insights, and translate abstract concepts into concrete, actionable habits.

---

## ✨ Key Features

- **Multi-Agent Orchestration**:
  - **Empathy Agent**: Active listening, emotional validation, and context framing.
  - **Research Agent**: Synthesizes mental models, philosophical frameworks, and targeted reading recommendations.
  - **Planner Agent**: Converts insights into structured reflection exercises and actionable habit routines.
- **Event-Driven Architecture**: Powered by Node.js `EventEmitter` for asynchronous multi-agent coordination and background processing.
- **Distraction-Free Interface**: Clean, minimalist UI focused on deep reflection and guided conversation.
- **Non-Clinical & Ethical Grounding**: Focuses strictly on mentorship, perspective-shifting, and mindset coaching without medical or psychiatric claims.

---

## 🛠️ Tech Stack

### **Frontend**
- **Framework**: React.js / Vite
- **Styling**: Tailwind CSS / Modern CSS
- **State Management**: Context API / React Hooks

### **Backend & AI**
- **Runtime**: Node.js / Express
- **Architecture**: Event-driven (`EventEmitter`) Multi-Agent System
- **LLM Orchestration**: Gemini API / LangChain

---

## 🏗️ System Architecture

```text
  [ User Interaction / React UI ]
                 │
                 ▼
      [ Express / API Gateway ]
                 │
      ┌──────────┴──────────┐
      ▼                     ▼
[ Event Bus ]  ◄──►  [ Agent Orchestrator ]
                            │
        ┌───────────────────┼───────────────────┐
        ▼                   ▼                   ▼
  [ Empathy Agent ]  [ Research Agent ]  [ Planner Agent ]
  (Active Listening) (Stoic/Jungian RAG)  (Actionable Habits)

```

---

## 🚀 Getting Started

### Prerequisites

* **Node.js** (v18.x or higher)
* **npm** or **yarn**
* LLM API Key (e.g., Google Gemini API key)

### Installation

1. **Clone the Repository**
```bash
git clone [https://github.com/arnab236/MindMentor.git](https://github.com/arnab236/MindMentor.git)
cd MindMentor

```


2. **Install Backend Dependencies**
```bash
cd backend
npm install

```


3. **Install Frontend Dependencies**
```bash
cd ../frontend
npm install

```


4. **Environment Setup**
Create a `.env` file in the `backend` directory:
```env
PORT=5000
GEMINI_API_KEY=your_api_key_here
NODE_ENV=development

```


5. **Run the Application**
*Start Backend:*
```bash
cd backend
npm run dev

```


*Start Frontend:*
```bash
cd frontend
npm run dev

```



---

## 📌 Disclaimer

**MindMentor is not a medical, psychiatric, or crisis intervention service.** It is an educational and self-development tool designed solely for mindset coaching, personal reflection, and philosophical exploration.

---

## 📄 License

This project is licensed under the [MIT License](https://www.google.com/search?q=LICENSE).
