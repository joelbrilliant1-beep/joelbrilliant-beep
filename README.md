# joel.brilliant

Hi, I'm Joel. I bridge the gap between Sales, Success, and Engineering. I use "Vibe Coding" (AI-assisted development) to build internal tools that automate complex workflows.

Role: Senior Solutions Engineer @ Sapia.ai

Focus: Developer Experience, Automation, Vibe Coding.

AI Stack: Large Language Models (GPT, Claude, Gemini, xAI) & Trae/Cursor.

### 🛠 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor_IDE-000000?style=for-the-badge&logo=cursor&logoColor=white)

### 🚀 Featured Projects

#### 1. Integration Agent (Proof of Concept)
*Automated Configuration Validator for Enterprise ATS Integrations.*
* **The Architecture:** A client-side validation engine designed to eliminate configuration errors before they reach the backend. It dynamically adapts its form logic based on the selected ATS (Workday, SuccessFactors, etc.), enforcing specific ID patterns and required fields.
* **Key Features:**
    * **Proactive Validation:** Implemented real-time regex checks to prevent common errors (e.g., preventing users from using an `ASSESS_CANDIDATE` ID where a Business Process ID is required).
    * **Standardized JSON Output:** Automatically generates a perfectly formatted JSON payload that matches the backend engineering schema, removing manual transcription errors.
    * **Dynamic UI Rendering:** Uses a lightweight state management system to conditionally render complex configuration forms for 10+ different ATS platforms without page reloads.
* **Tech:** HTML5, JavaScript (ES6+), Tailwind CSS, Lucide Icons.
* **Status:** 🔒 *Internal Source Code (Proprietary)*

#### 2. VibeJSON: Algo-Trading Execution Bot aka Trading Bot
*A Pine Script v6 Library for automated webhook signaling.*
* **The Architecture:** TradingView alerts typically send raw text. This custom library acts as a middleware layer, serializing trading logic into precise JSON payloads compatible with execution platforms.
* **Key Features:**
    * **WunderTrading Integration:** Automated entry/exit generation with type-safety checks.
    * **3Commas Automation:** Logic for "Smart Trade" entries and dynamic "Safety Orders" (DCA - Dollar Cost Averaging).
    * **String Sanitization:** Custom cleaning functions to prevent JSON parse errors in production.
* **Tech:** Pine Script v6, Webhooks, JSON.
* **Status:** 🔒 *Internal Source Code (Proprietary)*

#### 3. JD Studio Pro (Internal Tool)
*Automated Job Description Generator using OpenAI & Streamlit.*
* **The Architecture:** Unlike standard chatbots, this application forces the LLM (Gemini 2.5 Flash) to adhere to a strict JSON Schema. This ensures that every Job Description generated is machine-readable and fits perfectly into our frontend component blocks.
* **Key Features:**
    * **Schema-Constrained Generation:** Implemented strict object definitions to separate "The Hook," "Responsibilities," and "Success Profile" into discrete UI blocks.
    * **Multimodal Refinement:** Built a PDF-to-Base64 pipeline allowing the AI to ingest legacy documents and "refactor" them into the modern format.
    * **Block-Based Editor:** A React-based WYSIWYG editor allowing users to regenerate specific sections individually without rewriting the whole document.
* **Tech:** React, Tailwind (Glassmorphism UI), Google Gemini 2.5 API.
* **Status:** 🔒 *Internal Source Code (Proprietary)*

#### 4. Insights Storyteller
*Automated Business Intelligence & Narrative Engine.*
* **The Architecture:** A client-side React application that ingests raw recruitment metrics and utilizes Gemini 3 Flash to generate "Board-Ready" executive reports.
* **Key Features:**
    * **Privacy-First Architecture:** Implemented a client-side "PII Scrubber" toggle that sanitizes sensitive customer data (names, verbatim feedback) *before* the payload is sent to the AI model.
    * **Multimodal Context:** The app accepts both raw integer data and screenshot uploads (Vision API), allowing the AI to "read" legacy dashboard screenshots to validate manual data entries.
    * **Session Persistence:** Custom local-storage state management to prevent data loss during complex report generation sessions.
* **Tech:** React, Gemini 1.5 Flash, Tailwind CSS, Lucide.
* **Status:** 🔒 *Internal Source Code (Proprietary)*
