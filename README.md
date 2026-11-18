# 🛏️ Bed Bounce — *Khela ya nhi yeh* 😂🤣

## 🎮 Play Now

[![Play the Game](https://img.shields.io/badge/PLAY%20THE%20GAME-Click%20Here-brightgreen?style=for-the-badge)](https://xdotdex.github.io/Fuckgames/)
[![Telegram Bot](https://img.shields.io/badge/TELEGRAM%20BOT-@BedBouncebot-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/BedBouncebot)

▶️ **Web:** https://xdotdex.github.io/Fuckgames/ — no install, just open and play!
🤖 **Telegram:** [@BedBouncebot](https://t.me/BedBouncebot) — play right inside Telegram!

## 👤 Author

**DExTER** — follow / say hi:

- 📸 Instagram: [@callmedexter4.0](https://www.instagram.com/callmedexter4.0)
- ✈️ Telegram: [@xdotdexter](https://t.me/xdotdexter)
- 🐙 GitHub: [@XDOTDEX](https://github.com/XDOTDEX)

---

A tiny, silly **HTML5 canvas game** inspired by the viral bed-bounce video.
Stick figures with **real photo faces** fall from the sky — you drag the bed,
catch them, and watch them bounce off with the **actual sounds from the video**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)

## 🎮 How to Play

- **Drag** the bed left–right (touch, mouse, or `←` `→` arrow keys)
- Catch a falling guy on the bed → he **bounces off** with a *boing* from the original video — **+1 point**
- Miss him → **SPLAT!** 💥 — Game Over!
- Beat your own **BEST** score (saved automatically)

## ✨ Features

- 🧑 **Real faces from the video** — the sleeper in the bed and the falling guys use faces cropped from the original clip
- 🔊 **Real sounds from the video** — bounce, splat and game-over sounds sliced straight out of the video's audio, nothing skipped
- 📷 **Your face in the game** — upload any photo and it becomes the falling guys' face
- 🏆 Score + persistent **BEST** counter, just like the video's HUD
- ⏸️ Pause button & 🔊 sound on/off toggle
- 📱 Fully responsive — plays on phone and desktop, no install, no build step

## 🚀 Run It Locally

Just open **`index.html`** in any browser. That's it.

Or serve the folder:

```bash
npx serve .
# or
python3 -m http.server
```

**Python version:**

```bash
pip install pygame
python bed_bounce.py
```

## 📁 Files

| File         | What it is                                   |
|--------------|----------------------------------------------|
| `index.html` | Page structure + HUD + menus                 |
| `style.css`  | All styling (cream UI, like the video)       |
| `game.js`    | Game engine, physics, faces & sounds (vanilla JS + WebAudio fallback) |
| `bed_bounce.py` | Full **Python (pygame)** version of the game — same faces, sounds & gameplay |

## 🛠️ Tech

Pure **HTML5 Canvas + CSS3 + vanilla JavaScript**. Zero libraries, zero frameworks.
Sound effects are embedded clips from the original video (with synthesized WebAudio fallbacks).

---

*Made for friends, for laughs. Khela ya nhi yeh* 😂🤣
