# cv
This repository holds my resume and a cover letter example.

The main file for compiling the resume is [resume_cv.tex](resume_cv.tex). Sections included in the resume can be found under [cv-sections](/cv-sections).

The repository is synced to an [Overleaf](https://www.overleaf.com/) account which acts as the local development instance.

A [workflow](https://github.com/oisteinwind/cv/actions) has been set up with a [push-based trigger](https://github.com/oisteinwind/cv/blob/master/.github/workflows/generate_cv_pdf.yml) which builds the resume into a PDF file. This file is found [here](https://github.com/oisteinwind/cv/actions/workflows/generate_cv_pdf.yml). The action uses [latex-action](https://github.com/xu-cheng/latex-action) to produce the PDF.
