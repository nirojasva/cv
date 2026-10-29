# Nicolas Rojas Varela — Curriculum Vitae & Portfolio

[![Compile LaTeX CVs & Deploy Web Page](https://github.com/nirojasva/cv/actions/workflows/compile-cvs.yml/badge.svg)](https://github.com/nirojasva/cv/actions/workflows/compile-cvs.yml)
[![Live Web Page](https://img.shields.io/badge/Live%20Web%20Page-nirojasva.github.io%2Fcv-00f2fe?style=flat&logo=github)](https://nirojasva.github.io/cv/)
[![Download Latest PDFs](https://img.shields.io/github/v/release/nirojasva/cv?label=Latest%20PDFs&color=a855f7)](https://github.com/nirojasva/cv/releases/tag/latest)

Personal interactive portfolio and version-controlled LaTeX CVs of **Nicolas Rojas Varela**, Computer Science Engineer & CIFRE Industrial PhD Candidate at **Université Clermont Auvergne - LIMOS**.

---

## 🌐 Live Web Page
Access the interactive web page at: **[https://nirojasva.github.io/cv/](https://nirojasva.github.io/cv/)**

- **Bilingual**: Instant toggle between 🇬🇧 English and 🇫🇷 French.
- **Interactive UI**: Responsive dark theme, key metrics (85% detection rate, < 1s stream latency), publications at AAAI & NeurIPS with DOI/code links, and direct PDF downloads.

---

## 📄 CV Documents & Source Files

| Language | Profile | LaTeX Source | Download PDF |
|---|---|---|---|
| **English** | AI R&D Engineer / Research Engineer | [`cv_en_research.tex`](cv_en_research.tex) | [Download PDF](https://github.com/nirojasva/cv/releases/download/latest/cv_en_research.pdf) |
| **Français** | Ingénieur R&D en IA / Research Engineer | [`cv_fr_research.tex`](cv_fr_research.tex) | [Download PDF](https://github.com/nirojasva/cv/releases/download/latest/cv_fr_research.pdf) |

---

## ⚙️ Automated CI/CD Pipeline
Every push to `main` triggers a GitHub Actions workflow that:
1. Compiles LaTeX sources into PDF files using `xu-cheng/latex-action`.
2. Packages `index.html`, `style.css`, and the compiled PDFs into `_site`.
3. Automatically deploys the web page to **GitHub Pages**.
4. Releases the latest version of the PDFs under the `latest` tag release.
