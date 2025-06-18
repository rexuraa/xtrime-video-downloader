<h1 align="center">🌀 XTRIME VIDEO DOWNLOADER 🌀</h1>

<p align="center">
  <strong>High-Quality • Auto Watermark • Gallery Save • Serial Naming</strong><br>
  <img src="https://raw.githubusercontent.com/rexuraa/rexuraa_logo/main/rexuraa.png" width="120px"/>
</p>

---

## 📽️ What is XTRIME?

**XTRIME** is a powerful, Termux-compatible video downloader that:
- 🚀 Downloads videos in original **maximum quality**
- 🖼️ Automatically adds your **brand/logo watermark**
- 🔢 Automatically numbers videos like `Xtrime Video No.1`, `No.2`...
- 📁 Saves videos to the Android **Gallery (Download/XTRIME)**
- 🔁 Supports continuous downloads in one session

---

## ⚙️ Requirements

Install these once in Termux:

```bash
pkg update && pkg upgrade -y
pkg install python ffmpeg aria2 git -y
pip install rich yt-dlp
termux-setup-storage
git clone https://github.com/rexuraa/xtrime-video-downloader.git
cd xtrime-video-downloader
python xtrime.py
```
---
🟢 Then enter the video link when prompted:

🔗 Enter Video URL: https://www.youtube.com/watch?v=...

🟢 The tool will:

Download the video

Apply the watermark

Save it to: /sdcard/Download/XTRIME/

Name it like: Xtrime Video No.1.mp4, No.2.mp4 etc.

Broadcast to gallery auto-show


🔁 After each video, you'll see:

🔁 Download another video? (y/n):


---

🖼️ Logo Information

By default, the tool uses:

📁 /sdcard/DCIM/Xtrime/rexuraa.png

If this file doesn't exist, it automatically downloads the logo from:

https://raw.githubusercontent.com/rexuraa/rexuraa_logo/main/rexuraa.png

✅ You can change the logo anytime by replacing that PNG.


---

📦 Output Folder

All downloaded & watermarked videos are saved here:

/sdcard/Download/XTRIME/

Example:

Xtrime Video No.1.mp4
Xtrime Video No.2.mp4


---

💬 Example Preview

🌀 XTRIME VIDEO DOWNLOADER 🌀
Max Quality • Watermark • Serial Name • Gallery Save

🔗 Enter Video URL: https://youtube.com/abc123
📦 Estimated size: 58.23 MB
✅ Download complete!
🎬 Adding Watermark...
✅ Saved to Gallery: /sdcard/Download/XTRIME/Xtrime Video No.1.mp4
🔁 Download another video? (y/n): y


---

👨‍💻 Developer

Built with ❤️ by @rexuraa

> YouTube | Instagram | Facebook Downloader — Fast, Smart, and Simple




---

📬 Feedback or Support

Found a bug or want to suggest a feature?
📫 Open an issue or message me directly.


---

⭐ Star This Project

If you like this tool, don't forget to ⭐ star the repository to support future updates!
