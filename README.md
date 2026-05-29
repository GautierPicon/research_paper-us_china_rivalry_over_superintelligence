# Research Paper — US and China rivalry over superintelligence

This repository contains a research paper written in French on the technological rivalry between China and the United States, which addresses the following question: “In what ways does the technological rivalry between China and the United States pose a threat to future geopolitics?”

## Read the Paper

- Download it by clicking here: [DOWNLOAD](https://github.com/GautierPicon/research_paper-us_china_rivalry_over_superintelligence/raw/main/Research%20Paper%3A%20USA-China%20Rivalry%20Over%20Superintelligence.pdf)
- View it online on : [https://gautierpicon.github.io/research_paper1/](https://gautierpicon.github.io/research_paper1/)

## Contents

- Main
    - **`.github/workflows/build-pdf.yml`** — Automation that detects changes in the .lex file to automatically generate an updated PDF, which is then added to the [repository](https://github.com/GautierPicon/research_paper1/blob/main/Research%20Paper%3A%20USA-China%20Rivalry%20Over%20Superintelligence.pdf) and deployed to the [website](https://gautierpicon.github.io/research_paper1/)
    - **`.lex`** — LaTeX source file for the PDF document
    - **`.pdf`** — PDF automatically generated from the .lex source file
- gh-pages
    - **`.pdf`** — PDF uploaded to the website
    - **`index.html`** — ensures that the URL points to the PDF

## CI/CD

Every time a `.lex` file is pushed to `main`, GitHub Actions:

1. Compiles the `.lex` file into a PDF using `latexmk`
2. Commits the generated PDF to the `main` branch
3. Deploys the PDF to **GitHub Pages** (`gh-pages` branch)

The PDF is then accessible directly via [the repository’s GitHub Pages URL](https://gautierpicon.github.io/research_paper1/).
