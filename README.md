#context-aware-writing-ai
### Context-Aware AI Writing Assistant for Respectful Communication

context-aware-writing is an AI-powered writing assistant designed to detect and improve biased or harmful language toward Indigenous Peoples. It provides context-aware feedback, rewriting suggestions, and explanations to help users write in a respectful and inclusive manner.

---

## 🚀 Features
- ✨ Real-time writing detection with sentence-level analysis
- 🧠 Context-aware recommendations using a fine-tuned LLM
- 💬 Tooltip-based feedback and rewrite suggestions
- 🗂️ RAG (Retrieval-Augmented Generation) integration for Indigenous knowledge context
- 🔄 Continuous improvement via human feedback loops
- ⚙️ Chrome extension + Django backend architecture

---

## 🧰 Tech Stack
**Frontend:** JavaScript (Chrome Extension), React  
**Backend:** Python, Django, Supabase, OpenAI GPT-4o  
**Database:** PostgreSQL  
**AI Infrastructure:** RAG + vLLM Deployment  
**Hosting:** AWS EC2, Gunicorn, Nginx  

---

## 🧩 Architecture Overview
Chrome Extension → Django API → RAG Model → OpenAI GPT-4o → Supabase Feedback DB


- The Chrome extension sends user text sentence-by-sentence to the Django API.
- The API uses GPT-4o for language evaluation, assisted by RAG for contextual awareness.
- Supabase stores user feedback and model suggestions for continuous fine-tuning.

---

## 📊 Results & Impact
- Used by **pipikwan pêhtâkwan** to promote respectful communication online.
- Reduced false positives after integrating feedback loops.
- Currently deployed in internal testing with Indigenous organizations in Canada.

---

## 🧑‍💻 Author
**Sakina Alizada**  
AI Engineer

