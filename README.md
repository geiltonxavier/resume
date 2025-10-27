My resume written in LaTeX. https://geiltonxavier.dev/


docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex geilton_xavier_resume.tex

Forked from:
https://github.com/sb2nov/resume