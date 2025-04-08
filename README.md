## 🧠 Graph8 Full-Stack Migration Challenge: *PingCRM → React + FastAPI*

### Overview
You’ll be rebuilding the [PingCRM (Rails)](https://github.com/ledermann/pingcrm) open-source CRM app using a modern stack:

- **Frontend:** React + TypeScript  
- **Backend:** FastAPI (Python)  
- **Database:** PostgreSQL (required)  
- **Deployment:** Use free services (e.g., Vercel + Render + Supabase)

This is a real-world migration test. You’ll reference an existing Rails app but rebuild it fully in a new stack. We’re looking for clean structure, sensible decisions, and working features — not pixel-perfect design.

---

### ✅ Core Functionality to Rebuild

You should include:

1. **Contact Management**
   - List, create, edit, delete contacts
   - Each contact should have a name, phone, city, and associated company

2. **Company Management**
   - List and create/edit/delete companies
   - Associate contacts with companies

3. **Search & Filter**
   - Dashboard-style list with basic filtering or searching (by contact name or company)

---

### 🧰 Tech Stack Requirements

- **Frontend:**
  - React (with TypeScript)
  - React Router
  - Axios or Fetch
  - Tailwind CSS or any light styling

- **Backend:**
  - FastAPI
  - PostgreSQL (required — use Supabase, Render, or Neon for free hosting)
  - SQLAlchemy + Pydantic
  - CORS enabled

- **Deployment:**
  - **Frontend:** Deploy on [Vercel](https://vercel.com/) (free)
  - **Backend:** Deploy on [Render](https://render.com/) or [Deta](https://deta.space/) (free)
  - **Database:** Use [Supabase](https://supabase.com/) or [Neon](https://neon.tech/) (free Postgres hosting)

---

### 🎯 General Guidelines

- No need to implement user auth (assume the user is logged in)
- Feel free to use AI tools like GitHub Copilot or ChatGPT — we want to see how you use them smartly
- You will be evaluated on:
  - Structure and clarity of your code
  - API and frontend functionality
  - Sensible tech choices
  - Thoughtful error handling
  - Deployment completeness (bonus but strongly encouraged)

---

### 📦 Deliverables

Please submit a GitHub repo with this structure:

```
/frontend   (React + TypeScript)
/backend    (FastAPI)
/README.md  (includes instructions and links)
```

Your `README.md` should include:

- How to run the project locally (both frontend and backend)
- What database you used and how to connect
- Deployment URLs:
  - Live frontend on Vercel
  - Live backend on Render or Deta
  - Supabase/Neon link not required, but backend should be able to connect
- Notes on:
  - What’s complete or partially done
  - Time spent
  - What AI tools (if any) you used

---

### ⏱ Time Limit

Spend **no more than 4–5 hours** total on this. Prioritize:
- Functional features over polish
- Clear API and frontend structure
- Demonstrating your workflow

---

Would you like me to create a public version of this as a shareable `.md` file, Google Doc, or Notion page for candidates?
