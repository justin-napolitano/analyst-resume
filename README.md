# my-resume

A customizable LaTeX resume/CV template designed to provide a clean, professional layout with flexibility for personal style. Inspired by popular templates like AltaCV and AwesomeCV, this template runs on XeLaTeX and offers multiple page styles and color options.

---

## Features

- Clean and professional resume layout
- Multiple page styles with header and highlight bar options
- Support for single-sided and double-sided highlight bar placement
- Easily customizable colors and sections
- Compatible with XeLaTeX for advanced font and language support
- Includes example PDFs demonstrating layout possibilities

## Tech Stack

- **Primary Language:** TeX (LaTeX)
- **Build Script:** Python (for build automation)
- **Tools:** XeLaTeX, Makefile

## Getting Started

### Prerequisites

- XeLaTeX installed on your system
- Python 3 (for build automation)
- Make (optional, for build commands)

### Installation

Clone the repository:

```bash
git clone -b 8rivers https://github.com/justin-napolitano/analyst-resume.git
cd analyst-resume
```

### Build the Resume

You can compile the resume using XeLaTeX directly or use the provided build automation script.

To compile manually:

```bash
xelatex resume.tex
```

Or use the Makefile commands (if available):

```bash
make clean
make html
```

Alternatively, run the Python build script:

```bash
python3 python-build.py
```

## Project Structure

```
analyst-resume/
├── deployz/                 # Deployment related files (assumed)
├── sections/                # Resume sections as separate files (assumed)
├── my-resume.cls            # Custom LaTeX class file for the resume
├── resume.tex               # Main LaTeX source file
├── resume.pdf               # Compiled resume PDF
├── python-build.py          # Python script to automate build process
├── README.md                # This file
├── LICENSE                  # License file
├── *.jpeg / *.jpg           # Headshot and pictures used in resume
├── *.log, *.aux, *.out      # LaTeX compilation auxiliary files
├── resume-1.png, resume-2.png, resume-3.png  # Example output pages
└── technical.pdf            # Possibly a technical skills or projects PDF
```

## Future Work / Roadmap

- Add detailed documentation on customizing the template
- Support for additional output formats (e.g., HTML, DOCX)
- Enhance build automation with error handling and logging
- Add more example resumes showcasing different styles
- Integrate continuous integration for automatic PDF builds

---

*Note: This README is based on available files and inferred project structure.*