LaTeX-Leiden-University
=======================

A repository of LaTeX templates for Leiden University / Universiteit Leiden.


History MA Thesis
-----------------

Compiles on latest MacTeX 2012 with [biber](http://biblatex-biber.sourceforge.net) installed. It uses chicaco style citations in footnotes. The first mention to a citation is always a full citation, following citations are only the author name and the number to the full citation. This can be easily changed to Ibit. and Ibidem. by using verbose-ibid option instead of verbose-note. Have a look at p.73, [biblatex]([ftp://www.ctan.org/ctan/macros/latex/exptl/biblatex/doc/biblatex.pdf)

To change to biber, in TeXShop go to Preferences -> Engine and change BibTeX engine to `biber`.


To create the index for nomenclature, use this command: 

`makeindex Thesis.nlo -s nomencl.ist -o Thesis.nls`


Contribute
----------
Feel free to [fork](https://github.com/PatrickHeneise/LaTeX-Leiden-University/fork_select) and add more templates for other students to use or modifications of the History template.


License
-------

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">LaTeX-Leiden-University</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://about.me/PatrickHeneise" property="cc:attributionName" rel="cc:attributionURL">Patrick Heneise</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/">Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License</a>.