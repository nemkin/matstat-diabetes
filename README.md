# matstat-diabetes
Homework project for the Mathematical Statistics PhD course at BME.

## Generating Latex files

```bash
cd docs
jupyter nbconvert ../src/diabetes.ipynb --to latex
latexmk -pdf diabetes.tex
```
