# SarkaarSaathi – AI-Powered Government Assistant for Bharat 🇮🇳

![SarkaarSaathi Logo](file:///C:/Users/Aksaar%20Patel/.gemini/antigravity/brain/a9c9304d-d7d0-434d-afe3-3b556a6462aa/sarkaar_saathi_logo_1777316286591.png)

**Team Name:** AVERAGE BUDDHIMAN  
**Team Code:** UDB-LV8Z

---

## ❗ Problem Statement
Millions of Indian citizens face difficulty accessing government schemes due to:
*   **Complex language and legal jargon**
*   **Lack of awareness about eligible schemes**
*   **High rejection rates due to incorrect or missing documents**
*   **No guidance after rejection**

👉 **Result:** Time wasted, benefits lost, and frustration—especially in rural areas.

---

## 💡 Solution
**SarkaarSaathi** is an AI-powered platform that simplifies government processes by:
*   Helping users discover relevant schemes
*   Validating documents before submission
*   Generating appeals for rejected applications

👉 It provides a complete end-to-end solution — from **discovery → validation → approval**.

---

## 🔥 Core Features (3 Flows)

### 1️⃣ Benefit Hunter 
👉 **User enters:** Age, Income, State, Occupation.  
👉 **System:** Matches with relevant government schemes and shows benefits + eligibility.  
🎯 **Outcome:** User discovers schemes they didn’t know existed.

### 2️⃣ Document Validator 
👉 **User:** Selects service (Scholarship / MSME / License) and uploads required documents.  
👉 **System:** Checks validity using logic + OCR and shows **✅ READY** or **❌ NOT READY**.  
🎯 **Outcome:** Reduces rejection chances before applying.

### 3️⃣ Appeal Generator 
👉 **User:** Uploads rejection letter OR enters text.  
👉 **System:** Explains rejection in simple language and generates a professional appeal letter.  
🎯 **Outcome:** Helps user reapply and get approval.

---

## ⚙️ Tech Stack

### 🖥️ Frontend
*   React.js
*   Tailwind CSS

### 🔧 Backend
*   FastAPI (Python)

### 🤖 AI Layer
*   OCR (Text Extraction)
*   NLP (LLM for explanation & appeal generation)
*   Rule Engine (for validation & scheme matching)

### ☁️ Database & Auth
*   Firebase Authentication
*   Firestore Database

### 🌐 Deployment (Optional)
*   Vercel / Netlify (Frontend)
*   Render / Railway (Backend)

---

## ▶️ How to Run

### 🔹 1. Clone Project
```bash
git clone <your-repo-link>
cd project-folder
```

### 🔹 2. Run Frontend
```bash
npm install
npm run dev
```
👉 **Runs on:** [http://localhost:5173](http://localhost:5173)

### 🔹 3. Run Backend
```bash
cd backend
pip install fastapi uvicorn pandas python-multipart
uvicorn main:app --reload
```
👉 **Runs on:** [http://localhost:8000](http://localhost:8000)

### 🔹 4. Environment Variables
Create a `.env` file in the root directory and add your Gemini API Key:
```env
VITE_GEMINI_API_KEY=your_gemini_api_key
```

### 🔹 5. Setup Firebase
1.  Add Firebase config in `firebase.js`.
2.  Enable:
    *   **Authentication** (Email/Password)
    *   **Firestore Database**

---

**From confusion to approval — SarkaarSaathi stays with you at every step.**
