# PlymouthUniThesisTemplate
This is a PhD thesis template for Plymouth University, U.K. It is based on one available from Martin Coath (https://sites.google.com/site/mcoath/other/obscure-stuff/latex/uop-latex-stuff). I found his template invaluable, but there were various tweaks I needed to make as I wrote my thesis (specifically, some minor style changes, improved TOC links, organisational changes, and glossary functions). I started to use Martin's template in 2015, so it is possible that his later versions are more complete than this one. Nevertheless, I'm making this available as it may help someone with some tasks that took me time to figure out, or lead to improved forks from other users.

The template has been tested with Texmaker (http://www.xm1math.net/texmaker/), which is free and cross-platform. TeXcount was used for getting the word count (using count.bat). It uses a Perl script; installation is pretty straightforward: http://app.uio.no/ifi/texcount/.

This template is offered as-is. I do not plan to maintain it, so if the Plymouth University formatting requirements change, then this may be outdated.

Basic build steps:
1. (install glossaries package to your TeX distribution)
2. Run latex against 00_thesis.tex
3. Build the glossary (makeglossary %) against 00_thesis.tex
4. Build the document as usual (PDFLaTeX, BibTeX, PDFLaTeX, PDFLaTeX)

Whenever you modify the glossary make sure to rebuild it as in step 3, otherwise you can continue to just build as usual using PDFLaTex and BibTeX.
