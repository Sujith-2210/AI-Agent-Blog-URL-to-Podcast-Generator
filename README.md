# AI-Agent-Blog-URL-to-Podcast-Generator
# 📰 ➡️ 🎙️ Blog to Podcast Agent

Turn any blog post into an engaging podcast using AI!  
This Streamlit application scrapes blog content, summarizes it with Google Gemini, and generates audio using ElevenLabs.  

---

## 🚀 Features
- **Blog Scraping:** Extracts text from any blog URL using **Firecrawl**.  
- **Summarization:** Uses **Google Gemini** to create a concise, engaging summary (≤ 2000 characters).  
- **Podcast Generation:** Converts summaries into natural-sounding audio with **ElevenLabs**.  
- **Streamlit UI:** Simple interface for entering API keys, blog URLs, and downloading generated podcasts.  

---

## 🛠️ Requirements

### Python Packages
- `streamlit`
- `agno` (includes tools, agents, and utilities)
- `uuid`
- `os`

Install dependencies:
```bash
pip install streamlit agno
```

## 🔑 API Keys Required

### You need the following API keys:

- **Google Gemini API Key**

- **ElevenLabs API Key**

- **Firecrawl API Key**

These are entered in the Streamlit sidebar.

### ▶️ Running the App

Clone this repository:
```bash
git clone https://github.com/Sujith-2210/AI-Agent-Blog-URL-to-Podcast-Generator.git
```

### Run the Streamlit app:
```bash
streamlit run podcast.py
```

Enter your API keys in the sidebar.

Paste a blog URL and click 🎙️ Generate Podcast.

##📂 Output

Generated podcasts are stored in the audio_generations/ folder.

Files are saved as .wav and can also be downloaded from the UI.

### 📝 Example Workflow

Enter API keys.

Provide a blog URL.

Wait while the app scrapes, summarizes, and generates audio.

Play the podcast directly in the browser or download it.

⚠️ Notes

Summaries are limited to 2000 characters (due to ElevenLabs limits).

Requires all three API keys to function properly.

Errors will be displayed in the Streamlit interface.
