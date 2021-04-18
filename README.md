# CHR Bibliography

BibTeX collection of publications related to CHR. Source format for the [online publication list](https://about.chrjs.net/publications/).

## HTML Generation

With the help of [bibtex2html](https://www-sop.inria.fr/members/Gregoire.Malandain/codes/bibtex2html.html) by Grégoire Malandain, we can produce nicely formatted HTML pages. We make use of two separate files: `CHR.bib` is used for the real entries, while `bibtex2html.bib` contains the markup used by bibtex2html.

Having bibtex2html installed, simply run the following command to produce the HTML output:

```
cd /path/to/output-dir && bibtex2html -force /path/to/bibtex2html.bib /path/to/CHR.bib
```

Note that `bibtex2html` always uses the current working directory for its output.
