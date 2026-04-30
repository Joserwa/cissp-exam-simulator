# 🔐 CISSP Exam Simulator

A fully self-contained, offline CISSP practice exam simulator built as a single HTML file. No server, no internet connection, no installation required — just open in any browser.

![CISSP](https://img.shields.io/badge/Certification-CISSP-blue?style=flat-square)
![Domains](https://img.shields.io/badge/Domains-8%2F8-green?style=flat-square)
![Questions](https://img.shields.io/badge/Questions-859-orange?style=flat-square)
![Format](https://img.shields.io/badge/Format-Self--Contained%20HTML-lightgrey?style=flat-square)

**Can be accessed here also:** [CISSP Exam Simulator](https://joserwa.github.io/cissp-exam-simulator/CISSP_Exam_Simulator.html)
---

## 📋 Overview

This simulator mirrors the official ISC² CISSP examination format, including:

- **Official domain weighting** — questions are sampled per the ISC² published percentages
- **Two exam modes** — Full 700-question practice or 150-question CAT simulation
- **Real exam rules** — no answer feedback during the exam, only after submission
- **Timed sessions** — 6-hour countdown (700Q) or 3-hour (150Q) with auto-submit
- **Question navigator** — jump freely between questions, filter by unanswered or flagged
- **Score report** — scaled score out of 1000, domain breakdown, pass/fail verdict
- **Review mode** — review wrong answers and flagged questions with explanations

---

## 🗂️ Question Bank

**859 total questions** across all 8 CISSP domains, weighted per official ISC² exam outline:

| Domain | Questions | Exam Weight |
|--------|-----------|-------------|
| D1 · Security and Risk Management | 118 | 16% |
| D2 · Asset Security | 113 | 10% |
| D3 · Security Architecture and Engineering | 116 | 13% |
| D4 · Communication and Network Security | 111 | 13% |
| D5 · Identity and Access Management (IAM) | 103 | 13% |
| D6 · Security Assessment and Testing | 96 | 12% |
| D7 · Security Operations | 106 | 13% |
| D8 · Software Development Security | 96 | 10% |
| **Total** | **859** | **100%** |

Each exam session draws a **fresh random weighted sample** — so every attempt tests you differently.

---

## 🚀 How to Use

### Option 1 — Use directly from GitHub Pages (online)
If GitHub Pages is enabled on this repository:
1. Go to the repository **Settings → Pages**
2. Set source to `main` branch, root folder
3. Visit `https://<your-username>.github.io/<repo-name>/CISSP_Exam_Simulator.html`

### Option 2 — Download and run locally (fully offline)
1. Click the green **`<> Code`** button on this repository
2. Select **Download ZIP**
3. Extract the ZIP file
4. Double-click **`CISSP_Exam_Simulator.html`** to open in Chrome, Firefox, or Edge
5. No internet needed after download

---

## 🎯 Exam Modes

### Full Practice Exam (700 Questions)
- Mirrors the original CISSP written exam format
- 6-hour time limit
- Questions sampled proportionally across all 8 domains

### CAT Simulation (150 Questions)
- Mirrors the current Pearson VUE Computerized Adaptive Testing (CAT) format
- 3-hour time limit
- Same weighted domain sampling

---

## ⚙️ Features

| Feature | Details |
|---------|---------|
| 🔀 Fresh shuffle | Every session draws a new random weighted sample |
| 🚩 Flag & review | Flag questions mid-exam, review before submitting |
| 🔢 Question jumper | Jump directly to any question number |
| 📊 Progress bar | Live answered/remaining count in the top bar |
| ⏱️ Timer warnings | Turns amber at 1 hour, red + pulsing at 30 minutes |
| 📖 Review wrong | Post-exam review of wrong/unanswered with explanations |
| 🚩 Review flagged | Separately review all flagged questions post-exam |
| 📱 Mobile friendly | Responsive layout, slide-out navigator on small screens |
| 🌑 Dark mode | Optimised dark theme, easy on the eyes during long sessions |

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

*Built for CISSP candidates who want to practice under realistic exam conditions.*
