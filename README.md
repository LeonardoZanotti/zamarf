<img src="https://framalibre.org/sites/default/files/leslogos/pandoc.png" alt="Pandoc" />

# Zamarf
Zanotti's markdown to pdf converter. It can convert from html, txt and md to html, txt, md and pdf, and can convert from pdf to md.

## Requisites
You will need [python 3.7](https://www.python.org/downloads/) and install Pandoc, lmodern and some Textlive extensions. In debian derivades linux you can just do:
```bash
$ sudo apt-get install pandoc texlive-latex-base texlive-fonts-recommended texlive-extra-utils texlive-latex-extra lmodern
```
You also will need PDF-to-Markdown. Install it with:
```bash
$ pip install pdf-to-markdown
```

## How to use
```bash
# Clone this repository and enter him
$ git clone https://github.com/LeonardoZanotti/zamarf.git
$ cd zamarf/

# Running the program
$ python3 zabage.py file1.extension file2.extension

Available extensions: html, txt, pdf and md.
```

## References
You can search more about Pandoc [here](https://pandoc.org/index.html).

## LeonardoZanotti