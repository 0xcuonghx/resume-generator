# Overview
The personal resume using Latex
# Build
```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex cv.tex
```