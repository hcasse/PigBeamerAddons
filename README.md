# PigBeamerAddons
My resources for Latex Beamer presentations.

## Cheatcheat compilation

```
	$ pdflatex cheatsheet.tex
```


## Theme Use

Theme are mostly self-contained in a `.sty` file. Some may requires
additional files as images. In order to use a theme, you have to:
  * copy the .sty file in your document directory,
  * copy dependent files (usually a few) also,
  * in your presentation `.tex`file, use the theme with:

```
\usetheme{Archi}
```

Notice that the `sample.tex` may be useful to use the theme as each
theme may define its own set of color, *tikz* style and so on. Just
compile it and take a look at it:
```
	 $ cd THEME
	 $ pdflatex sample.tex
	 $ xdg-open sample.pdf
```

The theme and their compagnion files:
  * **Archi** (`board.png`)
