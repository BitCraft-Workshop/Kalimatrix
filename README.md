# Kalimatrix  
# YouTube / File Transcriber  

A simple, local desktop application to **download YouTube videos or playlists, convert audio/video to MP3/MP4, and generate subtitle files (SRT) with AI transcription** — all on your computer.  
No installation or setup — just download the release package, keep the folders together, and run the included **.exe**.  

---

## ✨ Features
- Download single YouTube videos or entire playlists  
- Extract audio as **MP3** with automatic conversion  
- Save video in **MP4** while still generating MP3 for transcription  
- Generate **.srt subtitle files** using Whisper AI transcription  
- Runs fully offline — no internet needed except to fetch YouTube videos  
- Easy-to-use GUI with progress and logs  

---

## 📦 How to Get Started
1. Go to the [Releases page](https://github.com/BitCraft-Workshop/Kalimatrix/releases).  
2. Download the latest `.zip` file.  
3. Unzip it to any folder on your computer.  
4. Inside the folder you’ll see:  
   - `YouTubeTranscriber.exe` → the program  
   - `bin/` → contains **ffmpeg** and **yt-dlp** (required, do not delete)  
   - `models/` → contains the Whisper AI model (required, do not delete)  
   - `assets/` → optional images/screenshots  
   - `README.md` → this file  

---

## 🖱️ How to Use
1. Double-click `YouTubeTranscriber.exe` to launch the app.  
2. To download from YouTube:  
   - Go to YouTube, click **Share → Copy link** (for videos or playlists).  
   - Paste the link into the app.  
3. Or click **Browse File** to pick a local media file (`.mp3`, `.mp4`, `.m4a`, `.webm`, `.wav`, `.mkv`).  
4. Choose your **Output Directory**.  
5. Select whether you want **Audio** (MP3), **Video** (MP4), or both.  
6. Click **Start Transcription**.  

**Results:**  
- Audio saved as **MP3**.  
- Video saved as **MP4**.  
- Subtitles saved as `.srt` with timestamps.  

---

## 📂 Package Layout
```
Kalimatrix-v1.0.0/
│
├─ YouTubeTranscriber.exe     # run this file
├─ bin/                       # yt-dlp + ffmpeg executables
├─ models/                    # whisper-large-v3 model
├─ assets/                    # screenshots or images
└─ README.md                  # instructions
```

---

## 📜 License
This project is licensed under the **MIT License** — see the LICENSE file.  

---

## 👤 Author
Created by **Muhammed (BitCraft Workshop)**  

- GitHub: [BitCraft-Workshop](https://github.com/BitCraft-Workshop)  
- Email: m.a.rabee@outlook.com  
