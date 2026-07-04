**Repository description** *(paste this in the GitHub description field)*:

`Interactive Islamic storybooks for children — animated HTML stories with audio narration, built on Ibn ʿArabī's spiritual teachings. Part of the Prophets of the Heart series.`

---
**README.md content:**

---
# 🌙 Prophets of the Heart — Interactive Storybooks

An open educational platform of interactive Islamic storybooks for children aged 6–8, combining Quranic accuracy, animated illustrations, audio narration, and the spiritual depth of Ibn ʿArabī.

---

## ✨ About the Project

Each story in this collection is a self-contained HTML file — no framework, no dependencies, no installation needed. Every prophet's story includes:

- 🎨 Animated SVG illustrations
- 🔊 Full audio narration with auto-advancing pages
- 💬 Interactive moments (choice questions, tap discoveries)
- 🌟 Ibn ʿArabī's spiritual teachings woven into child-appropriate language
- 📱 Fully responsive — works on phones, tablets, and desktop

The stories are designed to be read together by a parent and child, or listened to independently.

---

## 📁 Repository Structure

```
prophets-stories/
│
├── ibrahim/
│   ├── prophet_ibrahim.html
│   └── audio_prophet_ibrahim.wav
│
├── nuh/
│   ├── prophet_nuh.html
│   └── audio_prophet_nuh.wav
│
└── index.html          ← landing page (coming soon)
```

Each prophet has its own folder. Adding a new story means adding a new folder — nothing else changes.

---

## 🚀 How to Use

**Online:** Visit the live site at:
`https://prophets-stories.netlify.app/nuh/prophet_nuh.html`

**Locally:** Just open any `.html` file in your browser. No server needed for the story itself. For audio to work locally, serve via a local server:

```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000/nuh/prophet_nuh.html`

---

## 📖 Stories Available

| Prophet | Status | Language |
|---------|--------|----------|
| 🔥 Ibrahim (Abraham) | ✅ Live | English |
| 🚢 Nuh (Noah) | ✅ Live | English |
| More coming... | 🔄 In progress | — |

---

## 🎙️ Audio

Audio narration is recorded using **Kokoro TTS** (Heart voice) and exported as `.wav` files. The HTML file references the audio by filename — both files must be in the same folder.

Audio features:
- Pages advance automatically with the narration
- Play / pause button in the bottom navigation bar
- Interactive pause on choice questions — audio waits for the child's answer
- Resume from exact timestamp when child taps a response

---

## 🌿 Pedagogical Approach

Each story has three layers:

1. **The narrative layer** — the Quranic story told simply and accurately for a 6–8 year old
2. **The emotional layer** — the child's own experience reflected back (Your Flood, Your Ark)
3. **The spiritual layer** — Ibn ʿArabī's teachings on love, trust, and divine beauty, woven in gently

Stories are designed to be experienced, not just read. The child is never a passive listener.

---

## 👩‍💻 Author

**Lamyaa Sadouk, PhD** — AI researcher, university professor, and author of *Machine Learning Dévoilé*. Creator of educational digital content for children, including phonics apps (*Lecture Magique*, *Magic Reading*, *القراءة السحرية*) and Islamic educational platforms.

---

## 📄 License

Educational use freely permitted. Please credit the author if you share or adapt these stories.

---

*"And We carried him on a vessel made of planks and nails." — Quran 54:13*

---

You can copy this directly into a file called `README.md` at the root of your repository. GitHub will display it automatically on the repository's main page.
