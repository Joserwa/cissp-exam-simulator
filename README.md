# 🔐 CISSP Comprehensive Exam Simulator

A fully self-contained, offline CISSP practice exam simulator built as a single HTML file. No server, no internet connection, no installation required — just open in any browser.

![CISSP](https://img.shields.io/badge/Certification-CISSP-blue?style=flat-square)
![Domains](https://img.shields.io/badge/Domains-8%2F8-green?style=flat-square)
![Questions](https://img.shields.io/badge/Questions-1%2C268-orange?style=flat-square)
![Format](https://img.shields.io/badge/Format-Self--Contained%20HTML-lightgrey?style=flat-square)

**Can be accessed here also:** [CISSP Exam Simulator](https://joserwa.github.io/cissp-exam-simulator/CISSP_Exam_Simulator.html)

---

## 📋 Overview

This simulator mirrors the official ISC² CISSP examination format, including:

- **Official domain weighting** — questions are sampled per the ISC² published percentages
- **Four exam modes** — Full 700-question exam, 150-question CAT simulation, 100-question domain practice, or 50-question quick quiz
- **Study mode** — instant answer feedback per question with auto-advance on correct answers
- **Real exam rules** — no answer feedback during standard exam mode, only after submission
- **Timed sessions** — countdown timer per mode with auto-submit on expiry
- **Question navigator** — jump freely between questions, filter by unanswered or flagged
- **Score report** — domain breakdown with animated performance bars, pass/fail verdict
- **Review mode** — review wrong answers and flagged questions with full explanations
- **Keyboard shortcuts** — navigate and answer without touching the mouse

---

## 🗂️ Question Bank

**1,268 total questions** across all 8 CISSP domains — compiled and deduplicated from multiple source banks — weighted per the official ISC² exam outline:

| Domain | Questions | Exam Weight |
|--------|-----------|-------------|
| D1 · Security and Risk Management | 148 | 15% |
| D2 · Asset Security | 138 | 10% |
| D3 · Security Architecture and Engineering | 148 | 13% |
| D4 · Communication and Network Security | 193 | 13% |
| D5 · Identity and Access Management (IAM) | 175 | 13% |
| D6 · Security Assessment and Testing | 141 | 12% |
| D7 · Security Operations | 175 | 13% |
| D8 · Software Development Security | 150 | 11% |
| **Total** | **1,268** | **100%** |

Each exam session draws a **fresh random weighted sample** — so every attempt tests you differently.

---

## 🚀 How to Use

### Option 1 — Use directly from GitHub Pages (online)
Visit [CISSP Exam Simulator](https://joserwa.github.io/cissp-exam-simulator/CISSP_Exam_Simulator.html)

### Option 2 — Download and run locally (fully offline)
1. Click the green **`<> Code`** button on this repository
2. Select **Download ZIP**
3. Extract the ZIP file
4. Double-click **`CISSP_Comprehensive_Simulator.html`** to open in Chrome, Firefox, or Edge
5. No internet needed after download

---

## 🎯 Exam Modes

### Full Practice Exam (700 Questions)
- Mirrors the original CISSP written exam format
- 6-hour time limit
- Questions sampled proportionally across all 8 domains per ISC² weights

### CAT Simulation (150 Questions)
- Mirrors the current Pearson VUE Computerized Adaptive Testing (CAT) format
- 3-hour time limit
- Same weighted domain sampling

### Domain Practice (100 Questions)
- Focus on one or more specific domains using the domain filter
- 2-hour time limit
- Ideal for targeted study on weak areas

### Quick Quiz (50 Questions)
- Rapid knowledge check across all selected domains
- 1-hour time limit
- Great for daily warm-up sessions

---

## 📖 Study Mode

Toggle **Study Mode** on the intro screen to switch from exam simulation to active learning:

- Answers are revealed **immediately** after each selection
- The correct answer is always highlighted, even when you choose wrong
- Full explanation shown per question
- Automatically advances to the next question **0.8 seconds** after a correct answer
- Ideal for learning new material rather than simulating test conditions

---

## ⚙️ Features

| Feature | Details |
|---------|---------|
| 🔀 Fresh weighted shuffle | Every session draws a new random sample respecting domain weights |
| 📖 Study mode | Instant per-question feedback with auto-advance on correct answers |
| 🎹 Keyboard shortcuts | `A` `B` `C` `D` to answer · `←` `→` to navigate · `F` to flag · `Space` to advance |
| 🎨 Domain colour coding | Each domain has a unique colour in the navigator and results breakdown |
| 🚩 Flag & review | Flag questions mid-exam, review all flagged questions at any time |
| 🔢 Question jumper | Jump directly to any question number via the sidebar input |
| 📊 Live progress bar | Answered/remaining count and percentage updated in real time |
| ⏱️ Timer warnings | Turns amber below 30 minutes, red + pulsing below 5 minutes |
| 🗺️ Navigator sidebar | Colour-coded dots: blue = answered, amber = flagged, white = pending; green/red after submit |
| 🔍 Wrong/Skip review | Mid-exam or post-exam review of all wrong and unanswered questions |
| 📈 Domain breakdown | Animated performance bars per domain with colour-coded pass/warn/fail |
| 📋 Missed questions panel | Collapsible list of every missed question with your answer, correct answer, and explanation |
| 🌐 Domain filter | Select any combination of domains — the pool and stats update instantly |
| 📱 Mobile friendly | Responsive layout, sidebar hidden automatically on small screens |
| 🌑 Dark theme | Optimised dark UI, easy on the eyes during long study sessions |
| ✈️ Fully offline | Single HTML file — no dependencies, no CDN calls, works without internet |

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `A` / `B` / `C` / `D` | Select answer option |
| `←` | Previous question |
| `→` or `Space` | Next question |
| `F` | Toggle flag on current question |

---

## ⚠️ Disclaimer

> This simulator is an **unofficial** study aid and is **not affiliated with or endorsed by ISC²**.
>
> The question bank is intended as supplementary practice only. To maximise your chances of passing the real exam, combine this tool with:
> - **Official ISC² practice tests** (available at isc2.org)
> - **Boson ExSim for CISSP** (closest to real exam difficulty)
> - **The Official ISC² CISSP Study Guide** (Chapple & Stewart)
> - **Structured study** covering all 8 domains in depth
>
> The real CISSP CAT exam emphasises **managerial thinking** and **"most correct" scenario questions** — not purely factual recall. Always supplement with official materials.

---

## 📄 License

This project is released under the [MIT License](LICENSE). You are free to use, modify, and distribute it for personal and educational purposes.

---

## 🙏 Contributing

Pull requests are welcome. If you find incorrect answers, outdated content, or want to add questions:

1. Fork the repository
2. Create a feature branch (`git checkout -b fix/question-corrections`)
3. Make your changes
4. Submit a pull request with a description of what was changed and why

---

*Built for CISSP candidates who want to practice under realistic exam conditions — now with 1,268 questions across all 8 domains.*
