# 📄 ATS Resume Checker

A free, instant, and 100% private ATS (Applicant Tracking System) resume checker that runs entirely in the browser. No backend, no API, no data uploaded to any server.

![ATS Resume Checker](https://img.shields.io/badge/Status-Live-4fffb0?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![HTML](https://img.shields.io/badge/Built%20With-HTML%20%2F%20CSS%20%2F%20JS-ff6b6b?style=flat-square)
![PDF.js](https://img.shields.io/badge/PDF%20Parsing-PDF.js-ffd93d?style=flat-square)

---

## 🚀 Live Demo

👉 [https://yourusername.github.io/ats-resume-checker](https://yourusername.github.io/ats-resume-checker)

> Replace the URL above with your actual GitHub Pages link after deploying.

---

## ✨ Features

- **ATS Score (0–100%)** — Overall compatibility score with animated ring display
- **Keyword Analysis** — Checks 60+ common ATS keywords across tech, business, and soft skills
- **Section Detection** — Verifies presence of Experience, Education, Skills, Contact, Summary, and more
- **Score Breakdown** — Detailed scores for Keywords, Structure, Formatting, Content Length, and Impact
- **Issue Detection** — Flags missing email/phone, first-person language, table layouts, no LinkedIn, and more
- **Actionable Tips** — 8 quick-win recommendations to improve ATS pass rate
- **100% Private** — All analysis happens locally in your browser; no file is ever uploaded

---

## 🖼️ Preview

```
┌─────────────────────────────────────────┐
│         ATS Resume Checker              │
│                                         │
│    Drop PDF → Instant ATS Score         │
│    Keywords · Sections · Issues · Tips  │
└─────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 / CSS3 / Vanilla JS | Frontend (single file) |
| [PDF.js](https://mozilla.github.io/pdf.js/) (v3.11) | Client-side PDF text extraction |
| Google Fonts (Space Mono + Clash Display) | Typography |
| GitHub Pages | Hosting |

---

## 📁 Project Structure

```
ats-resume-checker/
├── index.html      # Entire app — single self-contained file
└── README.md       # This file
```

No dependencies to install. No build step. No framework.

---

## 🚀 Deploying to GitHub Pages

1. **Fork or clone** this repository
2. Make sure `index.html` is in the root of your repo
3. Go to your repo → **Settings** → **Pages**
4. Under *Source*, select `main` branch and `/ (root)` folder
5. Click **Save**
6. Your site will be live at:
   ```
   https://yourusername.github.io/ats-resume-checker
   ```

> It may take 1–2 minutes for GitHub Pages to go live after the first deploy.

---

## 🔍 How It Works

1. User uploads a resume PDF (drag & drop or file picker)
2. **PDF.js** extracts all text content from the PDF client-side
3. The text is analyzed against:
   - A library of 60+ ATS keywords (tech, business, general, soft skills)
   - Standard resume section names
   - Common ATS formatting issues
   - Quantified impact indicators
4. Scores are calculated across 5 dimensions and combined into a final ATS Score
5. Results are displayed instantly with keywords, issues, and tips

---

## 📊 Scoring Breakdown

| Category | Weight | What It Checks |
|----------|--------|----------------|
| Keyword Coverage | 30% | Matches against 60+ ATS keywords |
| Section Structure | 20% | Presence of standard resume sections |
| Formatting & Issues | 25% | Email, phone, layout, language issues |
| Content Length | 10% | Word count in optimal range (250–900) |
| Quantified Impact | 15% | Numbers, percentages, measurable results |

---

## ⚠️ Limitations

- Works only with **text-based PDFs** (not scanned images / photos of resumes)
- Keyword matching is generic — for best results, also tailor keywords to the specific job description
- Does not send your resume to any AI or cloud service (by design)

---

## 🤝 Contributing

Pull requests are welcome! Some ideas for improvement:

- [ ] Job description input field for custom keyword matching
- [ ] Support for `.docx` resume files
- [ ] Export results as PDF report
- [ ] Dark/light theme toggle
- [ ] More granular keyword categories by industry

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 👤 Author

Made by **[Your Name]**

- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)

---

> ⭐ If this project helped you, give it a star on GitHub!
