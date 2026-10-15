# 🌱 Eco-Receipt: AI-Powered Carbon Footprint Tracker

**Live Prototype:** <https://eco-receipt-fcb2f.web.app/>

Eco-Receipt is a smart, lightweight web application designed to track and calculate the carbon footprint of your daily shopping directly from receipt photos. By combining Google's Gemini Vision LLM with iimmersive interactive design, this app transforms abstract emission data into actionable, everyday insights.

## 🌍 Background & Vision

Our planet is facing unprecedented environmental challenges, yet most consumers remain unaware of the direct carbon impact of their daily grocery shopping. While the conversation around climate change often focuses on large factories or fossil fuels, individual consumption patterns play a massive role.

**Aligning with Google's Sustainability Mission:** Google has a strong vision for a greener future and a commitment to reaching Net-Zero emissions by 2030, actively pushing products that help users make eco-friendly choices (like eco-routing in Maps). Eco-Receipt shares this exact vision. I built this app to bring that same level of environmental awareness directly to the consumer's pocket, turning a piece of trash (thermal paper receipts) into a tool for environmental education.

## 💡 The Solution & Social Impact

Eco-Receipt takes a bottom-up approach to climate action. Instead of complex B2B dashboards, we focus on **Micro-Awareness and Behavioral Change**.

* **Micro-Awareness:** Translating complex CO₂e calculations into relatable metrics (e.g., "Equivalent to driving X km in a car").

* **Actionable Impact:** The AI doesn't just calculate; it provides 2-3 highly contextual, localized suggestions based on the specific items bought (e.g., "Swap one serving of beef with tempeh this week to save 50kg of CO₂e").

## ⚔️ Competitor Analysis

While there are existing GreenTech apps in the market (like Carbon Checkout, Climfy, or seCOia), Eco-Receipt differentiates itself significantly:

| Feature/Focus | Eco-Receipt (Our WebApp) | Existing Competitors | 
| ----- | ----- | ----- | 
| **Target Audience** | **B2C Educative.** Empowers everyday consumers to change habits. | **B2B / Checkout.** Focuses on enterprise POS integration or donation round-ups. | 
| **Data Input** | **Frictionless AI Vision.** Snap a photo of any receipt; the AI does the rest. | **Manual / API reliant.** Requires manual search or deep API integration with stores. | 
| **User Interface** | **Gamified & Emotional.** Dynamic Glassmorphism UI, weather/smoke particle effects, and generative soundscapes based on carbon scores. | **Static & Corporate.** Standard dashboards, tables, and rigid charts. | 

## ✨ Key Features

* **Frictionless Web App:** No installation required. Just open the link. It is highly lightweight and fully responsive (works flawlessly on Mobile, Tablet, and Desktop).

* **Vision AI Powered:** Uses Gemini's Multimodal capabilities to read crumpled, varied receipts, categorize items, and calculate lifecycle emissions.

* **Dynamic Visual & Audio Feedback:** The UI breathes. A "Green Score" of 80+ triggers a calming green atmosphere with birdsong (via Web Audio API), while a low score triggers a dark red interface with thunder and smoke particles.

* **Smart Safeguards:** The AI is strictly prompted to reject non-receipt images (e.g., faces, landscapes) to prevent hallucination.

* **Bilingual Support:** Seamlessly switch between English and Bahasa Indonesia.

* **Built-in Demo Mode:** Allows users and judges to experience the full UI/UX flow with sample data (Low, Mid, and High carbon examples) without needing to input an API key.

## 🔄 User Flow

1. **Access:** User opens the web app on their browser.

2. **Upload:** User snaps a photo of their grocery receipt using their camera or uploads one from their gallery.

3. **Process:** The image is compressed locally (to save data) and sent to the Gemini API.

4. **Analyze:** Gemini extracts the items, filters out non-products (taxes, change), calculates the CO₂e per item, and generates personalized eco-tips.

5. **Result:** The user sees their total carbon footprint, an eco-friendly score, a breakdown of high-emission items, and actionable advice to improve their next shopping trip.

## 🛠️ How We Built This (From Zero to Prototype)

This project is a testament to modern **AI-Assisted Development**. I built this entire application from scratch using **Google Gemini** as my AI coding partner.

By acting as the product architect, I collaborated with Gemini to rapidly translate my UX/UI vision into clean, functional code within a very short timeframe.

**Tech Stack:**

* **Frontend:** Pure HTML5, CSS3, and Vanilla JavaScript (No heavy frameworks, ensuring a blazing fast load time).

* **Styling:** Tailwind CSS (via CDN) for rapid, responsive layout creation.

* **Animations & Effects:** GSAP for fluid transitions and HTML5 `<canvas>` for dynamic smoke/weather particle rendering.

* **Audio:** Web Audio API for generative, real-time soundscapes without loading heavy `.mp3` files.

* **AI Engine:** Google Gemini API (`gemini-1.5-flash` for high-speed, multimodal inference).

* **Hosting:** Deployed seamlessly on **Firebase Hosting**.

## 🚀 Running Locally (For Judges)

The live app features a built-in UI to securely input your own API key for testing.

1. Clone this repository.

2. Open `index.html` in your browser (preferably via VS Code Live Server).

3. Expand the **"Gemini API key"** accordion and paste your key from Google AI Studio.

4. Upload a receipt and test the Live AI! (Leave the key blank to automatically try the interactive Demo Mode).