---
slug: github-analyst-resume-note-technical-overview
id: github-analyst-resume-note-technical-overview
title: Analyst Resume
repo: justin-napolitano/analyst-resume
githubUrl: https://github.com/justin-napolitano/analyst-resume
generatedAt: '2025-11-24T18:30:34.973Z'
source: github-auto
summary: >-
  This repo provides a customizable LaTeX resume template that emphasizes
  clarity and professionalism. Built with XeLaTeX, it features automation to
  simplify the resume-building process.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repo provides a customizable LaTeX resume template that emphasizes clarity and professionalism. Built with XeLaTeX, it features automation to simplify the resume-building process.

## Key Features

- Clean, professional layout
- Multiple page styles and customizable colors
- Single-sided and double-sided highlight options
- Example PDFs to showcase layouts

## Getting Started

To run this, clone the repo and switch to the default branch:

```bash
git clone -b 8rivers https://github.com/justin-napolitano/analyst-resume.git
cd analyst-resume
```

Ensure you have XeLaTeX and Python 3 installed. You can compile the resume via the command line:

**Manual:**

```bash
xelatex resume.tex
```

**With Makefile:**

```bash
make clean
make html
```

**Using Python script:**

```bash
python3 python-build.py
```

## Gotchas

Make sure you have the required software installed. Check the project structure for customization options and remember to keep your images in the right format.
