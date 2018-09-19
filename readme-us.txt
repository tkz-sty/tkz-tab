% utf8 
% version 1.4 01/06/2011 

A. Purpose

The 'tkz-tab' package is built on top of PGF and its associated front-end,
 TikZ and is a (La)TeX-friendly drawing package. The aim is to provide some
  useful macros  to build  tables showing variations  of functions as they are
   used in France.
These macros may be used by only LaTeX TeX users. The documentation is in 
 French.

B. Features
 -- works with utf8 and pdflatex
 -- provides 'help' option,
 -- allows to draw tables of variations with a "forbidden zone",
 -- allows to use TikZ.

C. Licence

You may freely use and distribute this package under the terms of  lppl and/or gpl.

Read file TKZdoc-tab.pdf.pdf in the doc directory, for the complete
 documentation

D. Contents of the folder (encoding utf8)

  -- README (this file)
  -- inputs: tkz-tab.sty
  -- doc: TKZdoc-tab.pdf, 
          tkz-doc.cls,
          tkzexample.sty,
          doctab.ist,
          TKZdoc-tab-adapt.tex
          TKZdoc-tab-examples.tex,
          TKZdoc-tab-images.tex,
          TKZdoc-tab-init.tex,
          TKZdoc-tab-install.tex,
          TKZdoc-tab-main.tex
          TKZdoc-tab-sign.tex,
          TKZdoc-tab-slope.tex,
          TKZdoc-tab-tangente.tex,
          TKZdoc-tab-tv.tex,
          TKZdoc-tab-valeurs.tex,
          TKZdoc-tab-variation.tex
          var-latin1.tex ( example with latin1)
          var-latin1.pdf
          sign-latin1.tex( example with latin1)
          sign-latin1.pdf
          
tkz-doc.cls is a class (beta version) to make the documentation. You need also
 the tkzexample.sty package (beta version) and KOMA-Script 2009/01/24 v3.02b to  compile the documentation.
          
E. Installation

If you need to install it by yourself, a TDS compliant zip archive is
provided (tkz-tab.zip).  Just download that file, and unpack it in
your TDS directory (~/texmf for Unix-like systems). If you only need to use
 'tkz-tab.sty' then you have to copy 'tkz-tab.sty' into '~/texmf/tex/latex'.
 If you want also to compile the documentation then you need to copy tkz-doc.cls and tkzexample.sty in the same folder and you need to use pdf(e)tex.

With MiKTeX, copy folder 'tkz-tab.sty' into 'C:\texmf\tex\latex', then
run 'MiKTeX Options'. In the 'File name database' section, click on
'Refresh now'.

F. The author of the 'tkz-tab.sty' package is Alain Matthes.
--
 Alain Matthes
 5 rue de Valence
 Paris 75005  
 
 al (dot) ma (at) mac (dot) com  

