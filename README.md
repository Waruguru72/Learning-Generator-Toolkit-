# Learning Generator Toolkit

## 📖 Project Overview

The **Learning Generator Toolkit** is a beginner-friendly AI tool that helps users quickly understand programming concepts, code snippets, and general knowledge topics. It detects if the input is code or text, provides easy-to-read explanations, supports dark mode, and allows you to download outputs as PDF.  

This project is built entirely with **free technologies** and can be run locally on your phone or deployed online.

---

## ⚡ Features

- **AI Explanation** – Ask questions about programming, technology, or general knowledge.  
- **Code Detection** – Automatically identifies if the input is a code snippet.  
- **Dark Mode** – Switch between light and dark themes.  
- **PDF Export** – Save AI outputs directly as PDF files for offline reading or submission.  
- **Free Stack** – Uses only free tools and free AI models (no paid APIs required).  

---

## 🛠 Tools & Technologies Used

- **Languages / Frameworks**
  - HTML, CSS, JavaScript (vanilla)
- **AI Backend**
  - Free OpenRouter API model: `meta-llama/llama-3-8b-instruct`
- **PDF Generation**
  - jsPDF (JavaScript library)
- **Editor**
  - Acode (for mobile coding)
- **Browser**
  - Chrome or any modern browser

---

## 📂 How to Run Locally

### Step 1: Open the Project
1. Open **Acode** (or any code editor)  
2. Open the file `index.html` in the folder `moringa` (or wherever you saved it)

### Step 2: Add Your API Key
1. Sign up at [OpenRouter](https://openrouter.ai/)  
2. Create a **free API key**:
   - Go to your profile → **API Keys** → **Create Key**  
3. In `index.html`, find:
```javascript
"Authorization": "Bearer "meta-llama/llama-3-8b-instruct""