# AI CV Template (LaTeX)

A clean, modular LaTeX CV template for researchers, engineers, and technical professionals in AI, software, and academia. Based on the resume structure of [Andrew R. Garcia, Ph.D.](https://andrewgarcia.vercel.app/), this template is designed for flexibility and clarity — with separate files for each section.

## 🌟 Features

- Modular section files (`/sections`)
- Clean layout with custom macros
- Easy to customize with placeholders like `{{ YOUR NAME }}`
- Supports links, awards, publications, conference talks, and projects
- Great for technical and academic CVs

## 📁 Directory Structure

```
ai-cv-template/
├── main.tex                # Main document
├── README.md               # You're here
├── sections/               # Individual section .tex files
│   ├── education.tex
│   ├── experience.tex
│   ├── skills.tex
│   ├── publications.tex
│   ├── conference.tex
│   ├── academic.tex
│   ├── certs.tex
│   ├── projects.tex
└── assets/
    └── preview.png         # (Optional) Screenshot of the CV
```

## 🚀 Quick Start

### 1. Clone this repo

```bash
git clone https://github.com/YOUR-USERNAME/ai-cv-template.git
cd ai-cv-template
```

### 2. Customize

Edit the placeholder fields like:

```latex
\contact{{{ YOUR NAME }}}{{{ YOUR LOCATION }}}{{{ EMAIL • WEBSITE • LINKEDIN }}}
```

Fill in content inside each `sections/*.tex` file.

### 3. Compile

Use your favorite LaTeX editor or run:

```bash
pdflatex main.tex
```

Or if you prefer automatic dependency resolution:

```bash
latexmk -pdf main.tex
```

> 💡 Tip: This template is tested with TeX Live and Overleaf.

## 📝 License

MIT License. Free for personal and commercial use.

---

Created by [Andrew R. Garcia](https://andrewgarcia.vercel.app/)  
Made open-source to help others build standout CVs in AI, engineering, and science.
