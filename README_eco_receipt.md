# 🌱 Eco-Receipt: Smart & Sustainable Digital Receipts

Eco-Receipt is a smart web application designed to track and calculate the carbon footprint of your daily shopping directly from receipt photos. 

Powered by contextual AI analysis (Google Gemini API), modern UI/UX (Glassmorphism & GSAP animations), and a focus on sustainable habit building, Eco-Receipt aims to change how we view the environmental impact of our everyday transactions.

## 🚀 Key Features

* **AI-Powered Carbon Analysis:** Upload a receipt and let Gemini AI instantly extract items, categorize them, and calculate the estimated carbon emissions (kg CO₂e).
* **Interactive & Premium Design:** A smooth, modern user experience featuring glassmorphism aesthetics, fluid GSAP animations, and dynamic weather/particle effects that change based on your carbon score.
* **Immersive Audio Experience:** Built-in generative soundscapes (Web Audio API) that adapt to your receipt's environmental impact.
* **Bilingual Support:** Seamlessly switch between English and Bahasa Indonesia.
* **Smart Modes:** Choose between "Live AI Mode" for real-time analysis or "Demo Mode" (with Low, Medium, and High carbon presets) to explore the app's features using sample data without needing an API key.

## 🛠️ How to Run Locally

To protect API credentials, the Gemini API key is not hardcoded into this public repository. You can safely run and test this project locally by following these steps:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/eco-receipt.git
   ```

2. **Open the project folder:**
   ```bash
   cd eco-receipt
   ```

3. **Run the application:**
   Since this is a vanilla HTML/JS/CSS project, you can simply open the `index.html` file directly in your browser. For the best experience, use a local server extension like **Live Server** in VS Code.

4. **Testing the Live AI Feature:**
   * Get your own Gemini API Key from [Google AI Studio](https://aistudio.google.com/apikey).
   * Open the Eco-Receipt app in your browser.
   * Expand the **"Gemini API key" accordion** on the main screen.
   * Paste your key into the input field. *(Note: Your key is only used in your local browser session and is never saved or sent anywhere else).*
   * Upload a receipt and click "Analyze Carbon Footprint"!

## 🔗 Live Prototype

You can try the live prototype of the application directly without any local setup here:
**[Insert your Firebase/Vercel Deploy Link Here]**

*Built for a greener future.* 🌍