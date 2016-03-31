# Latex Template

tldr: KOMA script based latex template for bachelor- and master-thesis (TH Wildau).

This repository contains a latex template for bachelor- and master-thesis at Technical University of Applied Sciences Wildau (Technische Hochschule Wildau, TH Wildau). **NOT OFFICIAL.** ... [because it doesn't exist](http://www.th-wildau.de/im-studium/fachbereiche/wir/wir-dokumente.html)

## Files
- [main.tex](main.tex) main file (to compile)
- [main.pdf](main.pdf) document preview
- [packages-settings](packages-settings.sty) self provided package, which include the packages and general settings
- [texmaker.tks](texmaker.tks) texmaker session file (e.g. define main file) - _update file paths_
- [chapters/00-prefix.tex](chapters/00-prefix.tex) prefix (abstract, indexes etc.)
- [chapters/01-chapter.tex](chapters/01-chapter.tex) main content - first chapter
- [chapters/02-chapter.tex](chapters/02-chapter.tex) main content - second chapter
- [chapters/03-chapter.tex](chapters/03-chapter.tex) main content - third chapter 
- [chapters/appendix.tex](chapters/appendix.tex) appendix

## Issues
You have an styling request or no idea to integrat things? Do not be frustrated. Use the [issus tracker](https://github.com/der-basti/de.th.wildau.latex/issues) or write me an email.

Please make a pull request of your improvements and share your knowledge.

## Setup

If you use the latest [texlive](https://www.tug.org/texlive/) version? You need the following packages to compile this latex document.

```$ tlmgr install csquotes acronym moderncv bigfoot xstring harvard blindtext```


## Distributions

- Windows: [MiKTeX](http://miktex.org/)
- Mac OS X: [MacTeX](https://www.tug.org/mactex/)
- Linux
	- Debian, Ubuntu: ```$ apt-get install texlive-full```
	- RedHat, CentOS: ```$ yum install tetex```

## Tools

You can write generally your .tex file in a simple text editor.

Useful free/open source tools are listed below:

- Editor
	- [Notepad++](https://notepad-plus-plus.org/) Win
	- [Texmaker](https://www.xm1math.net/texmaker/) Win, Mac, Linux
	- [TeXShop](http://pages.uoregon.edu/koch/texshop/) Mac
	- [TeXworks](https://www.tug.org/texworks/) Win, Mac, Linux
	- [Lyx](http://www.lyx.org/) Win, Mac, Linux, +
	- [TeXstudio](http://texstudio.sourceforge.net/) Win, Max, Linux, +
	- [Sublime Text](https://www.sublimetext.com/) Win, Mac, Linux
	- [Eclipse plugin TeXlipse](http://texlipse.sourceforge.net/) Win, Mac, Linux
- For equations
	- [LaTeXiT](https://www.chachatelier.fr/latexit/) Mac
- For bibliography
	- [BibDesk](http://bibdesk.sourceforge.net/) Mac
	- [JabRef](http://jabref.sourceforge.net/) java based
	- [citeulike](http://www.citeulike.org/) web based

My favorite tool chain are MacTeX (distribution), texmaker (editor), LaTeXiT and BibDesk.

[The Comprehensive TeX Archive Network (CTAN)](https://www.ctan.org/)
