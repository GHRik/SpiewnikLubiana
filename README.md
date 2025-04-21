# SpiewnikLubiana
[![Build PDF](https://github.com/GHRik/SpiewnikLubiana/actions/workflows/latex-pdf.yml/badge.svg)](https://github.com/GHRik/SpiewnikLubiana/actions)
![Last Commit](https://img.shields.io/github/last-commit/GHRik/SpiewnikLubiana)


<p align="center">
  <a href="https://ghrik.github.io/SpiewnikLubiana/index.html" target="_blank">
    <img src="https://img.shields.io/badge/Start%20singing!-PDF-red?style=for-the-badge"
         alt="Start singing!"
         width="800">
  </a>
</p>


## About this project

This repository contains a songbook written in LaTeX (`LubianaPiosenki.tex`).  
The project is configured so that any changes to the `.tex` file automatically trigger a GitHub Actions workflow that compiles the document to PDF and deploys the result to GitHub Pages.

The latest version of the PDF is always available at:

https://ghrik.github.io/SpiewnikLubiana/LubianaPiosenki.pdf

## What this project demonstrates

- Use of LaTeX to build a structured, typeset songbook with custom formatting and table of contents entries
- Automation of the build process using GitHub Actions
- Optimization of the CI pipeline to reduce LaTeX installation time
- Dynamic generation of version metadata (e.g. PDF timestamp)
- Separation of formatting and logical structure to prevent errors in table of contents generation

The setup is designed to be minimal and portable: it's enough to push a valid `.tex` file into the repository, and the GitHub workflow will handle the build and publish process automatically.

