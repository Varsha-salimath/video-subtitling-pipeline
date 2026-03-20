<div align="center">

# 🎬 Video Subtitling Pipeline

### ⚡ Turn any video into a fully subtitled video automatically

<p>
Built using <b>Python</b> • <b>FFmpeg</b> • <b>OpenAI Whisper</b>
</p>

</div>

---

## 🚀 Overview

This project is an **end-to-end automated video subtitling system**.

It takes a video as input, extracts audio, converts speech into text using AI, generates subtitle files, and embeds them back into the video — completely automatically.

---

## 🔄 Pipeline Flow

```

Video → Audio Extraction → Whisper Transcription → SRT Generation → Final Subtitled Video

```

---

## ✨ Features

- 🎧 Extracts audio from videos using FFmpeg  
- 🧠 Converts speech to text using Whisper AI  
- 📝 Generates accurate `.srt` subtitle files  
- 🎬 Burns subtitles directly into video  
- 📂 Supports multiple videos (batch processing)  
- ⚡ Fully automated workflow  

---

## 🛠️ Tech Stack

- Python  
- FFmpeg  
- OpenAI Whisper (Local Model)  
- subprocess, tqdm, argparse  

---

## 📁 Project Structure

```

video-subtitling-pipeline/
│
├── input/
├── output/
├── temp/
│
├── my_utils/
│   ├── audio.py
│   ├── transcribe.py
│   ├── srt_generator.py
│   └── video.py
│
├── main.py
├── requirements.txt
└── README.md

````

---

## ⚙️ Setup

### 1. Install dependencies
```bash
pip install -r requirements.txt
````

### 2. Install FFmpeg

Make sure FFmpeg is installed and added to PATH:

```bash
ffmpeg -version
```

---

## ▶️ Usage

1. Add videos to:

```
input/
```

2. Run:

```bash
python main.py
```

3. Output will be saved in:

```
output/
```

---

## 💡 Example

**Input:**

```
input/video.mp4
```

**Output:**

```
output/video_subtitled.mp4
```

---

## 🧠 Key Learnings

* Real-world file handling in Windows
* Integrating external tools (FFmpeg + Python)
* Building AI-powered pipelines
* Debugging environment & path issues
* Managing temporary processing files

---

## ⚠️ Notes

* 💸 No cost — uses local Whisper model
* ⚡ Performance depends on CPU
* ⏳ Large videos take more time

---

## 🚀 Future Improvements

* GUI interface (drag & drop)
* Multi-language subtitles
* Faster processing (parallel execution)
* Subtitle styling options

---

<div align="center">

### ⭐ If you like this project, give it a star!

</div>
```

---

# 🔥 WHY THIS FIXES YOUR PROBLEM

Your new README will:

✅ Be **centered at top (clean look)**
✅ Have **clear sections (not messy text)**
✅ Look like a **real production project**
✅ Be **easy for recruiters to scan** ([Fabreco Studio][1])

---

# 🎯 Small extra tip (VERY important)

After pasting:

👉 Click **Preview** tab (top left in GitHub editor)

If it looks clean → then:

👉 Click **Commit changes**

---

# 💬 Next level (optional)

If you want it EVEN better:

* Add demo video 🎥
* Add badges (stars, license)
* Add screenshot

---
