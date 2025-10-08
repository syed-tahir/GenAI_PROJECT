# GenAI Video Summarizer 🎥🧠

**GenAI Video Summarizer** is an intelligent tool that takes a YouTube video link as input and generates a concise textual summary using advanced generative AI techniques. It helps users quickly understand the key content of videos without watching the entire duration.

## 🔍 Features

- 🎯 Accepts YouTube video links
- ✂️ Transcribes video using speech-to-text APIs
- 📄 Summarizes the content using LLM (Large Language Model)
- ⚡ Provides fast and relevant summaries
- 🧠 Built for students, researchers, and content consumers

## 🚀 How It Works

1. **Input:** User submits a YouTube video link.
2. **Extraction:** Audio is extracted from the video.
3. **Transcription:** Audio is converted to text using models like Whisper.
4. **Summarization:** The transcript is summarized using an LLM (e.g., GPT, LLaMA).
5. **Output:** Clean, readable summary is displayed.

## 🛠️ Tech Stack

- Python
- OpenAI Whisper / SpeechRecognition (for transcription)
- Transformers / LangChain / OpenAI API (for summarization)
- Streamlit / Flask (for UI, optional)
- pytube / youtube_dl (for downloading YouTube videos)

## 📦 Installation

```bash
git clone https://github.com/syed-tahir/GenAI_PROJECT.git
cd GenAI_PROJECT

pip install -r requirements.txt

## 🧪 Usage

python app.py

Then open the local server (e.g., localhost:8501) and paste the YouTube video URL to generate the summary.

## 🧠 Example

Input:
🔗 https://www.youtube.com/watch?v=dQw4w9WgXcQ

Output:
"This video discusses the importance of staying motivated, never giving up, and the role of optimism in achieving long-term goals..."

## 📌 Future Enhancements

Add support for multi-language transcription

Enable chapter-wise summarization

Integrate with note-taking apps (Notion, Obsidian, etc.)

Export summaries to PDF or markdown


## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

MIT License © 2025 Syed Mohammed Tahir

---
