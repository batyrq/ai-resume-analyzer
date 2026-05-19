# AI Resume Analyzer

Upload your resume and get instant AI-powered feedback, score, and improvement tips — powered by Groq API.

---

## Screenshot

> _Add a screenshot of the app here_

![App Screenshot](screenshot.png)

---

## Features

- **PDF Upload** — drag-and-drop or browse to upload your resume as a PDF; text is extracted automatically via pdf.js
- **Paste Text** — alternatively paste your resume content directly into the text area
- **Overall Score** — animated circular gauge (0–100) color-coded green / yellow / red
- **Letter Grade** — A through F grade badge based on resume quality
- **ATS Score** — dedicated ATS (Applicant Tracking System) compatibility score with animated progress bar
- **Strengths** — what your resume does well, highlighted in green
- **Weaknesses** — areas that need attention, highlighted in red
- **Improvement Tips** — concrete, actionable suggestions highlighted in blue
- **Missing Keywords** — important industry keywords absent from your resume, shown as chips
- **Dark Modern UI** — fully responsive, works on desktop and mobile

---

## How to Use

1. **Get a free Groq API key** at [console.groq.com](https://console.groq.com)
2. **Open `index.html`** directly in your browser — no server or build step needed
3. **Paste your Groq API key** into the key field (it is saved in your browser's `localStorage`)
4. **Upload your resume** as a PDF or paste the text manually
5. Click **Analyze Resume** and wait a few seconds for results

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML, CSS, JavaScript (no frameworks) |
| AI Model | Groq API — `llama-3.3-70b-versatile` |
| PDF Parsing | [pdf.js](https://mozilla.github.io/pdf.js/) 3.11.174 (CDN) |
| API Key Storage | Browser `localStorage` |

---

## License

[MIT](LICENSE)
