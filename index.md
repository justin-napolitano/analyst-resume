---
slug: "github-analyst-resume"
title: "analyst-resume"
repo: "justin-napolitano/analyst-resume"
githubUrl: "https://github.com/justin-napolitano/analyst-resume"
generatedAt: "2025-11-23T08:12:46.615823Z"
source: "github-auto"
---


# Building a Custom LaTeX Resume Template: My Journey with `my-resume`

Hey there! I’m Justin Napolitano, and today I want to share a bit about a personal project I’ve been working on: a LaTeX resume template called `my-resume`. If you’re like me, you want your resume to look professional, clean, and tailored to your style — but sometimes existing templates don’t quite fit the bill. That’s where this project comes in.

## Why I Built `my-resume`

When I was searching for a resume template, I found a lot of great options like AltaCV and AwesomeCV. They’re fantastic, but I needed something that did exactly what I wanted without extra fluff. Plus, I wanted full control over the layout and styling, and to use XeLaTeX for better font and language support.

So I took inspiration from those projects and built my own template from the ground up. It’s designed to be simple yet flexible, letting me customize headers, highlight bars, colors, and page styles easily.

## What Problem Does It Solve?

Resumes are often the first impression you make on a potential employer. Having a clean, well-structured resume that stands out without being over the top is crucial. Many templates are either too basic or too complex, and customizing them can be a pain.

`my-resume` strikes a balance by providing a professional layout that’s easy to tweak. It supports multiple page styles — like having a header and highlight bar on the first page and a simpler layout on subsequent pages. It also supports single-sided or double-sided highlight bars, which helps if you want to print or share your resume in different formats.

## How It’s Built

The core of the project is written in TeX, specifically designed to run on XeLaTeX. This allows me to use modern fonts and handle multilingual text smoothly.

To automate building the resume, I wrote a Python script (`python-build.py`) that runs commands like `make clean` and `make html` to compile the LaTeX source. This script also installs any dependencies needed (though currently minimal) and helps keep the build process smooth.

The project structure is modular, with separate folders for deployment scripts (`deployz`) and sections of the resume (`sections`). The main class file (`my-resume.cls`) encapsulates the styling and layout logic, making it easy to update the look and feel.

## Interesting Implementation Details

- **Highlight Bar Options:** The template supports different highlight bar placements — on the left side for all pages (single-sided) or alternating sides for double-sided printing. This is controlled via options in the class file.

- **Multiple Page Styles:** There are different pagestyles implemented, like a full header with highlight bar on the first page and a simpler style on others, which helps keep the resume clean and readable.

- **Build Automation:** The Python build script uses subprocess calls to run `make` commands and can be extended to include git operations for version control.

- **Example PDFs and Images:** The repo includes example pages (`resume-1.png`, `resume-2.png`, `resume-3.png`) demonstrating different layout possibilities, which is great for visualizing how to customize the template.

## Why this project matters for my career

Creating `my-resume` was more than just building a resume template — it was about honing my skills in LaTeX, automation, and project structuring. It’s a tangible example of my ability to take inspiration from existing tools and tailor them to my exact needs.

Moreover, having a professional, customizable resume template means I can quickly update and adapt my resume for different opportunities, which is invaluable in a fast-moving job market.

Lastly, sharing this project publicly shows my commitment to quality and continuous improvement, qualities I value deeply as a developer and analyst.

---

Thanks for reading! If you’re interested in LaTeX, resume design, or build automation, feel free to check out the repo and customize it for your own needs. Happy TeXing! 🎉