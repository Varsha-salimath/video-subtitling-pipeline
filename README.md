# 🎬 Automated Video Subtitling Pipeline

Turn any video into a fully subtitled video — automatically.  
This project uses **OpenAI Whisper + FFmpeg** to generate accurate subtitles and embed them directly into videos.

---

## 🚀 What This Project Does

This pipeline automates the complete subtitling process:
Video → Audio → Speech-to-Text → SRT → Final Subtitled Video

No manual work. Just drop videos and run.

---

## ✨ Features

- 🎧 Extracts audio from video using FFmpeg  
- 🧠 Converts speech to text using Whisper (AI)  
- 📝 Generates properly formatted `.srt` subtitle files  
- 🎬 Burns subtitles into the video  
- 📂 Supports batch processing (multiple videos at once)  
- ⚡ Fully automated pipeline  

---

## 🛠️ Tech Stack

- **Python**
- **FFmpeg**
- **OpenAI Whisper (local model)**
- `subprocess`, `tqdm`, `argparse`

---

## 📂 Project Structure
video-subtitling-pipeline/
│
├── input/ # Place your videos here
├── output/ # Final subtitled videos
├── temp/ # Temporary processing files
│
├── my_utils/
│ ├── audio.py # Audio extraction
│ ├── transcribe.py # Whisper transcription
│ ├── srt_generator.py# Subtitle generation
│ └── video.py # Subtitle embedding
│
├── main.py # Main pipeline
├── requirements.txt
└── README.md

---

## ⚙️ Setup Instructions

### 1️⃣ Install dependencies

```bash
pip install -r requirements.txt
2️⃣ Install FFmpeg

Download and add FFmpeg to PATH
Verify:ffmpeg -version
3️⃣ Run the pipeline
python main.py
📌 Usage

Add videos to:

input/

Run the script:

python main.py

Get results in:

output/
💡 Example

Input:

input/video.mp4

Output:

output/video_subtitled.mp4
🧠 Key Learnings

Handling real-world file paths (Windows issues)

Integrating external tools (FFmpeg with Python)

Building end-to-end automation pipelines

Managing temporary files efficiently

Debugging system-level errors (PATH, subprocess)

⚠️ Notes

Uses local Whisper model → No API cost 💸

Processing speed depends on your CPU

Large videos may take longer

🚀 Future Improvements

🔥 Add GUI (drag & drop interface)

🌍 Multi-language subtitle support

⚡ Parallel processing for faster batch execution

🎨 Subtitle styling (fonts, colors)

💼 Use Cases

Content creators (YouTube, Instagram)

Online courses

Accessibility (hearing-impaired users)

Video automation pipelines

⭐ Why This Project Stands Out

This is not just a script — it’s a complete AI-powered automation system combining:

Machine Learning (Whisper)

System Integration (FFmpeg)

Backend Engineering (Python pipeline)

👩‍💻 Author

Varsha Salimath

⭐ If you like this project

Give it a ⭐ on GitHub!
