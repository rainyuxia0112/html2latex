html2latex
==========

convert html to latex

Dependencies
------------
Arch Linux: `# pacman -S python3 python-lxml python-cssutils python-cssselect`

Ubuntu: ``# apt install python3-lxml python3-cssutils python3-cssselect`

Pip: `pip3 install lxml cssutils cssselect`

Usage
-----
`example.py [--input HTML FILE] [--output TEX FILE] [--style CSS FILE]`

* To convert a HTML/XHTML file to LaTeX:
`./example.py --style stylesheet.css --input document.html --output document.tex`
* To convert several HTML files at once, just add more `--input` and `--output` arguments:
`./example.py --style stylesheet.css --input document.html --output document.tex --input other.xhtml --output other.tex`

Make a copy of `example.py` and modify it.


