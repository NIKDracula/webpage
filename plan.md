## 💬 Chatbot Portfolio Integration – Specification Sheet

### 🧩 Project Overview
**Goal**: Develop a chatbot named `nikol.AI` for your HTML/CSS/JS-based portfolio website, allowing visitors to interact with a smart, friendly assistant that introduces you and answers questions about your CV, projects, and career.

**Technologies**:
- Frontend: HTML, CSS, JavaScript
- Backend Logic: n8n workflows
- Chatbot Engine: Mistral AI via API

---

### ✅ Phase 1: Project Initialization **(Completed)**  
You’ve already completed:
- GitHub portfolio setup
- Core website structure
- n8n setup (local/cloud)
- Finalized Mistral as your chosen LLM backend

---

### 💬 Phase 2: Chatbot UI Integration
**Objective**: Add branding and interface to your homepage.

- [ ] 🎨 Design or place a temporary `nikol.AI` logo
- [ ] 💬 Embed a lightweight chat widget on the front page
- [ ] 📜 Display welcome message:
  _"Hi, I’m nikol.AI 🤖 — Nikolay's digital assistant! Curious about the portfolio, experience, or CV? Just ask!"_
- [ ] 🧪 Build JavaScript-driven input/output chat box (no backend yet)

---

### 🔌 Phase 3: Backend Prototype – Mistral Integration via n8n
**Objective**: Create a working chatbot pipeline.

- [ ] 🧠 Build n8n workflow using Mistral’s **Generate Text** node
- [ ] 🔗 Connect front-end chat widget to n8n via **Webhook** or REST API
- [ ] 🧪 Send user questions from site → n8n → Mistral → back to site
- [ ] 🔄 Return formatted responses dynamically in the chat box

---

### 📚 Phase 4: Content Staging & Chatbot Awareness
**Objective**: Prepare the site’s reference materials and mock data.

- [ ] 🗂️ Draft summaries for CV, bio, project list, contact info
- [ ] 📄 Create a placeholder knowledge base or context that Mistral can reference
- [ ] 🧪 Test chatbot answers with simulated content (e.g., “Tell me about Nikolay’s teaching background”)

---

### 🛠️ Phase 5: Refinement & Response Tuning
**Objective**: Improve chatbot personality and reliability.

- [ ] 🎯 Tailor prompt engineering for tone (friendly, witty, professional)
- [ ] 🔁 Add fallback messages for unclear queries
- [ ] 💡 Consider loading conversation history or recent questions to improve continuity
- [ ] 🖼️ Refine branding/logo, positioning, and color scheme
- [ ] 🧪 Add simple confidence checks or response ratings

---

### 🌐 Phase 6: Final Launch & Portfolio Showcase
**Objective**: Publish and feature `nikol.AI` as a portfolio highlight.

- [ ] 🚀 Merge chatbot code with live portfolio site
- [ ] 🔒 Double-check access, permissions, and hosting security
- [ ] 📝 Write a short blog or case study on how you built nikol.AI
- [ ] 📽️ Optional: Record demo video or animation showing real-time chat experience

