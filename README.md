# analyst-resume

A customizable LaTeX resume template designed for clarity, professionalism, and flexibility. This project provides a clean layout powered by XeLaTeX with build automation to streamline resume generation.

---

## Features

- Clean and professional resume layout using LaTeX
- Multiple page styles with header and highlight bar options
- Support for single-sided and double-sided highlight bar placement
- Easily customizable colors and sections
- Compatible with XeLaTeX for advanced font and language support
- Build automation via Python script and Makefile
- Example PDFs included demonstrating layout options

## Tech Stack

- **Primary Language:** TeX (LaTeX)
- **Build Script:** Python
- **Tools:** XeLaTeX, Makefile

## Getting Started

### Prerequisites

- XeLaTeX installed on your system
- Python 3
- Make (optional)

### Installation

Clone the repository and switch to the default branch:

```bash
git clone -b 8rivers https://github.com/justin-napolitano/analyst-resume.git
cd analyst-resume
```

### Build the Resume

You can compile the resume manually or use the provided automation.

**Manual compilation:**

```bash
xelatex resume.tex
```

**Using Makefile:**

```bash
make clean
make html
```

**Using Python build script:**

```bash
python3 python-build.py
```

## Project Structure

```
analyst-resume/
├── deployz/                 # Deployment related files (assumed)
├── sections/                # Resume sections as separate files (assumed)
├── my-resume.cls            # Custom LaTeX class file defining resume styles
├── resume.tex               # Main LaTeX source file
├── resume.pdf               # Compiled resume output
├── python-build.py          # Python script automating build process
├── README.md                # Project documentation
├── LICENSE                  # License information
├── *.jpeg / *.jpg           # Headshot and other images used in resume
├── *.log, *.aux, *.out      # LaTeX build artifacts
```

## Future Work / Roadmap

- Expand build automation to support additional output formats
- Add more customizable templates and color schemes
- Improve documentation with usage examples and troubleshooting
- Integrate CI/CD for automated build and deployment

---

*Note: Some assumptions on folder contents and deployment details are based on file names and typical LaTeX project structure.*