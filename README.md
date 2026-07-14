<div align="center">

# 🎧 Web Music Player

A sleek, fully responsive web-based music player built with **HTML5, CSS3, and vanilla JavaScript**. Play, pause, skip, shuffle, and repeat your favorite tracks — all with a smooth, modern UI.

Built as part of the **Crixsoft Solution Web Development Internship** 🚀

</div>

---

## 📸 Preview

![Music Player Preview](./readme-images/desktop.png)

## ✨ Features

- ▶️ **Play / Pause** — control playback with a single click
- ⏭️ **Next / Previous** — skip through the playlist
- 🔀 **Shuffle** — play tracks in random order
- 🔁 **Repeat** — loop the current track (repeat one)
- 📃 **Playlist Display** — view all songs with title, artist, and album art
- 📊 **Progress Bar** — live seek bar showing current playback position and duration
- 🔊 **Volume Control** — adjust playback volume on the fly
- 📱 **Fully Responsive** — works seamlessly across desktop, tablet, and mobile

## 🛠️ Built With

- **HTML5** — semantic markup and audio API
- **CSS3** — custom styling, flexbox/grid layout, responsive design
- **JavaScript (Vanilla)** — DOM manipulation and playback logic
- **Material Symbols** — icon set for player controls

## 📁 Project Structure

```
music-player/
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── images/          # album posters
│   ├── js/
│   │   └── script.js    # player logic
│   └── music/           # audio tracks
├── favicon.svg
├── index.html
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- [Git](https://git-scm.com/downloads) installed on your machine

### Run Locally

```bash
# Clone the repository
git clone https://github.com/<abrarquadri>/Crixsoft-Solution_Web-Music-Player.git

# Navigate into the project folder
cd Crixsoft-Solution_Web-Music-Player

# Open index.html in your browser
```

No build steps or dependencies required — it's pure HTML, CSS, and JS.

## 🎯 How It Works

1. The playlist is rendered dynamically from a JavaScript array of song objects.
2. Clicking a song loads it into the player and starts playback via the HTML5 `<audio>` element.
3. The progress bar updates in real time using the `timeupdate` event, and users can seek by clicking/dragging it.
4. Next, Previous, Shuffle, and Repeat all manipulate the current track index in the playlist array.

## 📌 Internship Submission Note

This project was completed as part of the **Web Development Internship at Crixsoft Solution**.

- ✅ Task completed and pushed to a GitHub repository named `Crixsoft Solution_Web-Music-Player`
- ✅ Internship status shared on LinkedIn, tagging **@Crixsoft Solution**
- ✅ Project completion posted on LinkedIn with a short video walkthrough

## 📬 Contact

**Crixsoft Solution**
🌐 [www.crixsoftsolution.com](http://www.crixsoftsolution.com)
📧 info@crixsoftsolution.com
💼 [LinkedIn](https://www.linkedin.com/in/abrarquadri)

## 📄 License

This project is free to use for learning and internship submission purposes.
