# 👁 Words That Think — 1984 Vocabulary Builder

> *Increase your vocabulary. Strengthen your thought.*

A beautifully designed vocabulary study app built around George Orwell's *Nineteen Eighty-Four*. Learn 102 words from the novel through its own sentences, then test your knowledge and spelling.

---

## ✨ Features

- **102 vocabulary words** drawn directly from *1984*, organised into 10 groups
- **Bilingual definitions** — English and Chinese (中文) for every word
- **Synonyms & antonyms** shown as colour-coded chips for each entry
- **Two authentic sentences per word:**
  - 📖 The original Orwell quotation in context
  - 💡 An AI-generated thematic example, aligned in spirit with the novel
- **Group Quiz** — fill-in-the-blank using Orwell's own sentences (multiple choice)
- **✏️ Spell It quiz** — type the missing word from the AI example; letter-by-letter feedback
- **★ Starred words** — star words you want to revisit; a dedicated starred quiz unlocks at 5+ stars
- **My Sentences** — write up to 3 of your own example sentences per word, saved locally
- **Text-to-speech** — hear any word pronounced
- **Mobile-first swipe navigation** — full-screen swipe cards optimised for phones

---

## 📱 Mobile Experience

On phones and tablets, the app enters a full-screen swipe mode automatically:

| Gesture | Action |
|---|---|
| Swipe left | Next word |
| Swipe right | Previous word |
| Tap bottom ★ | Open starred list |
| Tap bottom 📝 | Open group quiz |

Add to your iPhone or Android home screen for a native app experience — no browser chrome, full screen.

---

## 🚀 Getting Started

### Option 1 — Use the live version
👉 **[words-that-think.github.io](https://words-that-think.github.io)** *(replace with your actual GitHub Pages URL)*

### Option 2 — Run locally
Download `Words_That_Think_1984.html` and open it in any modern browser. No server or installation needed — it is entirely self-contained.

---

## 🗂 Repository Structure

```
Words_That_Think_1984.html   ← The entire app (self-contained)
manifest.json                ← PWA manifest for "Add to Home Screen"
README.md                    ← This file
```

---

## 📚 Vocabulary Groups

| Group | Words | Chapters |
|---|---|---|
| 1 | vile → predicament | Part I, Chs. 1–2 |
| 2 | bigoted → equivocal | Part I, Chs. 2–4 |
| 3 | vaporized → lucid | Part I, Chs. 4–6 |
| 4 | ecstasy → annihilation | Part I, Chs. 6–8 |
| 5 | monstrous → unalterable | Part II, Chs. 1–4 |
| 6 | annihilate → perpetuate | Part II, Chs. 4–9 |
| 7 | crimestop → doublethink | Newspeak & Appendix |
| 8 | blackwhite → proletariat | Part II–III |
| 9 | versificator → varicose | Part I–III |
| 10 | frowsy → nebulous | Part I–III |

---

## 🧩 Quiz Modes

### Group Quiz (📝)
Multiple-choice fill-in-the-blank using Orwell's original sentences. One quiz per group of 10–11 words.

### Spell It (✏️)
The AI example sentence is shown with the target word blanked out. Type the word. Individual letter boxes show you exactly which letters are right and which are wrong.

### Starred Quiz (★)
Unlock when you have starred 5 or more words. Works the same as the Group Quiz but draws only from your starred list.

---

## 🛠 Technical Notes

- **Single file** — the entire app is one `.html` file (~118 KB). No frameworks, no build tools, no external dependencies.
- **System fonts only** — Georgia (serif) + `-apple-system` (sans-serif). No web font requests.
- **localStorage** — stars, personal sentences, and quiz scores are saved in your browser. Clearing browser data will reset them.
- **No server needed** — works offline once loaded. Host anywhere: GitHub Pages, Netlify, or a USB stick.
- **PWA-ready** — pair with `manifest.json` for a native-app experience on mobile.

---

## 📖 Attribution

Vocabulary selection, app design, AI example sentences, and Chinese translations are original work.

Orwell quotations are from *Nineteen Eighty-Four* by George Orwell (1949). The novel is in the public domain in many jurisdictions. This project is for personal educational use only and is not affiliated with the Orwell estate or any publisher.

---

## 📄 License

The application code and original content are released under the **MIT License**.

Orwell's original sentences are quoted for educational purposes under fair dealing / fair use doctrine.

---

*"Who controls the past controls the future. Who controls the present controls the past."*
