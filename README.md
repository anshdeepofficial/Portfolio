# Anshdeep Singh — Portfolio Website

A modern, responsive personal portfolio website built to showcase skills, projects, education, certifications, and contact information with an integrated on-page chatbot experience.

## Live Website

- **GitHub Pages:** https://anshcreates.vercel.app/
## Features

- Premium dark-themed responsive UI
- Hero, about, skills, projects, resume, and contact sections
- Interactive project cards and animated visual effects
- Contact modal for quick outreach
- Integrated website chatbot aligned with the portfolio design
- Standalone terminal chatbot (`chatbot.py`) for rule-based Q&A

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Python (for terminal chatbot)

## Project Structure

```text
Portfolio/
├── index.html              # Main portfolio website
├── chatbot.py              # Terminal chatbot script
├── README.md               # Repository documentation
├── README_CHATBOT.md       # Chatbot-focused usage notes
├── CNAME                   # Custom domain configuration
└── .github/workflows/
    └── static.yml          # GitHub Pages deployment workflow
```

## Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Ansh200618/Portfolio.git
   ```
2. Open the project folder:
   ```bash
   cd Portfolio
   ```
3. Launch the website by opening `index.html` in your browser.

> Keep `RESUME.pdf` in the repository root so the **Download Resume** button can download it directly.

## Terminal Chatbot

Run the chatbot script:

```bash
python3 chatbot.py
```

The chatbot supports portfolio queries such as skills, projects, education, certifications, contact, and experience.

## Deployment

This repository is configured for GitHub Pages deployment through `.github/workflows/static.yml` on pushes to the `main` branch.

## Contact

- **Email:** anshdeep200618@gmail.com
- **GitHub:** https://github.com/Ansh200618
- **LinkedIn:** https://www.linkedin.com/in/anshdeep-singh-editor
