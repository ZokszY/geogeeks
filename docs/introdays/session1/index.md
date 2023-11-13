

# Session #1 support material/info

## Markdown

[Geogeeks page about Markdown](../../writing/markdown.md)

!!! external-link "Markdown Guide Getting Started"
    
    [Arguable the best cheat-sheet!](https://www.markdownguide.org/cheat-sheet/)

    [markdown-cheat-sheet.md](https://www.markdownguide.org/assets/markdown-cheat-sheet.md)    


- exercise #1: [HTML page to replicate](md_result.html) (use PyCharm)
- exercise #2: convert your .md file to a PDF with [Pandoc](https://pandoc.org/) 

- - -

## LaTeX

[Geogeeks page about LaTeX](../../writing/latexintro.md)

### Intro slides (as presented during GEO1002)

[Intro slides to LaTeX](../../writing/files/intro_latex_tudelft3d.pdf) by [tudelft3d](https://3d.bk.tudelft.nl)

### Exercises

  1. Register at <https://overleaf.com> with your `@tudelft.nl` email (for an account with more options, TUDelft pays for it)
  1. Start with the template below here and discover/try some features. Notice that this won't compile correctly because of the reference on line 26: the file `myreferences.bib` should be in the same folder
  1. copy the content of the second file to a file `myreferences.bib` and add it to the same folder
  1. check this [demo template](https://github.com/tudelft3d/latex-getting-started/tree/main/template) to know the best way to make complex things (tables, code, etc.)
  1. when all this works, try to replicate [this PDF](latex_result.pdf)


### A better starting template for simple LaTeX

```tex
\documentclass[a4paper,11pt]{scrartcl}

\usepackage{graphicx}
\usepackage[utf8]{inputenc} %-- pour utiliser des accents en français
\usepackage{amsmath,amssymb,amsthm} 
\usepackage[round]{natbib}
\usepackage{url}
\usepackage{mathpazo}
\usepackage{booktabs}
\usepackage{hyperref}

\title{My great title}
\author{Jan Smit\\ \url{j.smit@tudelft.nl}}
\date{\today}

\begin{document}

\maketitle

\section{Introduction}

Lemongrass frosted gingerbread bites banana bread orange crumbled lentils sweet potato black bean burrito green pepper springtime. 
Strawberry ginger lemongrass agave green tea smoky maple tempeh glaze enchiladas couscous. 
Cranberry spritzer Malaysian cinnamon pineapple salsa apples spring cherry bomb bananas blueberry pops scotch bonnet pepper.

Bento box roasted peanuts pasta Sicilian~\citep{DeVries20}.

\bibliographystyle{abbrvnat}
\bibliography{references.bib}

\end{document}
```

```tex
@article{DeVries20,
  author = {De Vries, Piet},
  doi = {10.1016/j.scs.2022.104225},
  journal = {Sustainable Cities and Society},
  pages = {102222},
  title = {Understanding the relationship between urban morphology and other things},
  year = {2021}
}
```

- - -


## Python venv

[Geogeeks page about venv](../../python/venv.md)

1. [install pyenv](../../python/install.md)
1. [create a new venv](../../python/venv.md) called "geogeeks"
1. activate it (with the console or with PyCharm)
1. install [pyproj](https://pyproj4.github.io/pyproj/): `pip install pyproj`
1. try to import it: `import pyproj` and you shouldn't get any errors

- - -

## Today's slides

Today's slides are available [there](https://surfdrive.surf.nl/files/index.php/s/n2P6iWSHehFtop8).