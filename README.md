# AI_Reel_Generator🎬
 

A Python + Flask web app that allows users to upload images and automatically generates Instagram Reels using **FFmpeg** and **ElevenLabs** AI-generated audio.

---

## 🚀 Features
✅ Upload images via the web interface  
✅ Generate Instagram Reel videos with FFmpeg  
✅ Use ElevenLabs API for AI-generated audio narration  
✅ Final reels saved in `static/reel/`  

---

## ⚙️ Tech Stack
- **Python**
- **Flask**
- **FFmpeg**
- **ElevenLabs API**

---

## 📝 Setup & Usage

### 1️⃣ Clone the repository

git clone https://github.com/rishan2004/AI_Reel_Generator.git
cd AI_Reel_Generator
---
### 2️⃣  Install FFmpeg
FFmpeg is required for video processing.

Windows: Download from https://ffmpeg.org/download.html and add to PATH

### 3️⃣ Add your ElevenLabs API key
Create a file called config.py in the root folder and write this:
ELEVENLABS_API_KEY = "your_api_key_here"

### 4️⃣ Run the app
Start both processes:

# Start Flask app
python main.py

# Start the reel generation process
python generate_process.py

### 5️⃣  View your reel
Your generated reel will be saved at:
static/reel/
or you can see the reel in the "Gallery" menu in the web

