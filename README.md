# Photo Slideshow App

A Flask‑powered web app to upload images, customize slide durations/transitions, add audio, and generate downloadable video slideshows using MoviePy & FFmpeg.

---

## 🚀 Features
- **User Auth & Admin Panel**: Secure signup/login plus an admin dashboard.  
- **Image Management**: Upload, preview & delete photos.  
- **Slideshow Builder**: Select images, set per‑slide duration & transition style.  
- **Audio Support**: Upload your own track or pick from library.  
- **Video Generation**: Combines images and audio into MP4 via MoviePy/FFmpeg.  
- **Preview & Download**: Watch your slideshow in‑browser or download the final video.

---

## 🛠 Tech Stack
- **Backend**: Python 3 · Flask · Flask‑MySQLdb / psycopg2 · JWT · bcrypt  
- **Video**: MoviePy · FFmpeg  
- **Frontend**: HTML · CSS · JavaScript · Bootstrap  
- **Database**: CockroachDB (PostgreSQL protocol)  

SlideShow/
├─ app.py             # Flask routes & slideshow logic
├─ root.crt           # DB SSL certificate
├─ static/            # CSS, JS, images, HTML templates
└─ .vscode/           # Editor settings (optional)

## Author
- **Parth Tokekar**
- **Email: parth.tokekar@students.iiit.ac.in**
- **GitHub: github.com/PatGB5**

