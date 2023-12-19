# ThesisTemplate
A Latex template for academic papers, designed by graphic Designers for readability and style.
This template is orginally designed for students and academics of the Games Master program at the University of applied Science Hamburg (HAW Hamburg). The graphic design is by Prof. Ralf Hebecker and adapted to Latex by Andreas Gaschka.

## How to use this template

* Clone this repo
* Download and install the Font `Lato` either from Google Fonts or Adobe Creative Cloud (which I recommend).
* Use your favorite Tex editor to write, preview and render your document (I recommend Texpad for Mac).
* Edit `ThesisTemplate.tex`

## Get the font

https://fonts.google.com/specimen/Lato

https://fonts.adobe.com/fonts/lato

## Options

### layout-options.tex 
This file contains the option to toggle the page layout to be either a single page or a two page layout. Comment out the according line. You configure and toggle the crop margin in here as well, please consult the docs of your printing house to set the correct values. Further you can toggle the visibily of layout guide.

### configuration.tex
This file includes all the packages to style the document and contains a lot of options to be touched by advanced graphic designers only.

## Workflow tipps

I recomend to use Zotero to collection and organize your research:

https://www.zotero.org

Export your bibliography from Zotero using the Better Bibtex format and replace Bibliothek.bib:

https://github.com/retorquere/zotero-better-bibtex

Now you can drag and drop your cite keys from Zotero right into you latex doc.

## Words with Hyphen (Trennstrich) and line breaks

If your text contains words composed of two words with a hyphen inbetween (like DJ-Setup), in rare cases the used hyphenation can cause doubled hyphen at the end of a line. Write `DJ\-/Setup` instead, to force a single hyphen before the line wrap.