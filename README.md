# ⚡ Vibe Script

**Vibe Script** helps content creators instantly generate high-engagement, perfectly formatted short-form video captions without the fatigue of manual formatting or complex prompting.

## 🚀 One-Sentence Pitch
Our app helps short-form content creators turn raw video ideas into ready-to-publish, thumb-stopping captions using Gemma 4.

## 🛠️ Tech Stack & Model Details
* **Frontend/UI:** Streamlit (Python)
* **AI Core Engine:** Google GenAI SDK
* **Model Used:** `gemma-4-26b-a4b-it`
* **Model License:** Apache 2.0
* **Project License:** MIT License

## 💡 Core Features
* **Zero-Prompting:** Turn one rough sentence into a polished caption layout.
* **Platform-Specific Presets:** Instantly tailors length and tone for TikTok, Instagram Reels, or YouTube Shorts.
* **Thumb-Friendly Formatting:** Automatically structure outputs with an aggressive hook line, clear vertical line breaks, and stacked hashtags.

## ⚙️ How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com
   cd vibe-script
   ```

2. Install dependencies:
   ```bash
   pip install streamlit google-genai python-dotenv
   ```

3. Configure your environment variables:
   Create a `.env` file in the root directory and add your Google AI Studio API key:
   ```text
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. Launch the application:
   ```bash
   streamlit run app.py
   ```
