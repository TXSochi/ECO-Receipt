# 🌱 Eco-Receipt: Smart & Sustainable Digital Receipts

**Live Prototype:** [https://eco-receipt-fcb2f.web.app/](https://eco-receipt-fcb2f.web.app/)

Eco-Receipt is a smart, lightweight web application designed to track and calculate the carbon footprint of your daily shopping directly from receipt photos. By combining Google's Gemini Vision LLM with immersive interactive design, this app transforms abstract emission data into actionable, everyday insights.

> **Created by Norch Team:** 
> * **Michael Christianto** 
> * **Ruwanti Eka Rahayu**

---

## 🌍 Background & Vision

Our planet is facing unprecedented environmental challenges, yet most consumers remain unaware of the direct carbon impact of their daily grocery shopping. While the conversation around climate change often focuses on large factories or fossil fuels, individual consumption patterns play a massive role.

**Aligning with Google's Sustainability Mission:** Google has a strong vision for a greener future and a commitment to reaching Net-Zero emissions by 2030, actively pushing products that help users make eco-friendly choices. Eco-Receipt shares this exact vision, turning a piece of trash (thermal paper receipts) into a tool for environmental education.

## 💡 The Solution & Social Impact

Eco-Receipt takes a bottom-up approach to climate action. Instead of complex B2B dashboards, we focus on **Micro-Awareness and Behavioral Change**:
* **Micro-Awareness:** Translating complex $\text{CO}_2\text{e}$ calculations into relatable metrics (e.g., "Equivalent to driving $X$ km in a car").
* **Actionable Impact:** The AI provides 2–3 highly contextual, localized suggestions based on specific items bought (e.g., swapping beef for tempeh).

## ✨ Key Features

* **Frictionless Web App:** No installation required, lightweight, and fully responsive across Mobile, Tablet, and Desktop. Also supports **PWA (Progressive Web App)** for home-screen installation.
* **Vision AI Powered:** Uses Gemini's Multimodal capabilities to read varied receipts, filter non-product lines, categorize items, and calculate lifecycle emissions.
* **Dynamic Visual & Audio Feedback:** The UI breathes. A high green score triggers a calming green atmosphere with generative audio, while a low score triggers a dark red interface with smoke particle effects.
* **Smart Safeguards:** The AI is strictly prompted to reject non-receipt images to prevent hallucinations.
* **Bilingual Support:** Seamlessly switch between English and Bahasa Indonesia.
* **Built-in Demo Mode:** Allows users and judges to experience the full UI/UX flow without needing an API key.

## ⚔️ Competitor Differentiation

| Feature / Focus | Eco-Receipt (Our WebApp) | Existing Competitors | 
| :--- | :--- | :--- | 
| **Target Audience** | **B2C Educative.** Empowers everyday consumers. | **B2B / Checkout.** Focuses on enterprise POS integration. | 
| **Data Input** | **Frictionless AI Vision.** Snap a photo; the AI does the rest. | **Manual / API reliant.** Requires manual search or deep store integration. | 
| **User Interface** | **Gamified & Emotional.** Dynamic Glassmorphism UI, particle effects, and generative soundscapes. | **Static & Corporate.** Standard dashboards and rigid charts. | 

## 🛠️ How We Built This (AI-Assisted Development)

This project was built from scratch using modern **AI-Assisted Development** workflows. 
* **Frontend:** HTML5, Vanilla JavaScript (ES6+), and Tailwind CSS via CDN.
* **Animations:** GSAP for fluid transitions and HTML5 Canvas for weather/smoke particle effects.
* **Audio:** Web Audio API for real-time generative soundscapes.
* **AI Engine:** Google Gemini API (Multimodal Vision).
* **Hosting:** Deployed on **Firebase Hosting**.

## 🚀 Running Locally (For Evaluation)

To protect API credentials, the default Gemini API key is left blank in public deployment. You can easily test the Live AI feature locally:

1. Clone this repository and open `index.html` (or use VS Code Live Server).
2. Expand the **"Gemini API key"** accordion on the main screen.
3. Paste your API key from [Google AI Studio](https://aistudio.google.com/apikey). *(Your key stays securely in your local browser session).*
4. Upload a receipt and test! *(Leave blank to automatically try the interactive Demo Mode).*