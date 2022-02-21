Eric Weise's resume


# Prerequisites
```bash
sudo apt install texlive-latex-extra
```


# Building Documents
```bash
pdflatex -interaction nonstopmode resume.tex
pdflatex -interaction nonstopmode curriculum-vitae.tex
```


# Uploading PDFs
```
mv resume.pdf eric-weise-resume.pdf
mv curriculum-vitae.tex eric-weise-cv.pdf
git add eric-weise-resume.pdf eric-weise-cv.pdf
git commit -m 'Updated PDFs'
git push origin master
```
