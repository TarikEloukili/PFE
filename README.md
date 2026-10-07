# PFE

This is my work on my final year (PFE) report at BCG X / INPT. All sensitive data were blurred or removed.

## **[Report (PDF)](PFE%20REPORT/main.pdf)**

## **[Defense Presentation (PDF)](PRESENTATION/PFE_Defense.pdf)**

## How to replicate

Install Linux on your laptop, then:

```bash
# install the LaTeX distribution and the build tool
sudo apt install texlive-full latexmk

# compile the report (runs pdflatex as many times as needed)
cd "PFE REPORT" && latexmk -pdf main.tex
```

The result is `main.pdf`.
