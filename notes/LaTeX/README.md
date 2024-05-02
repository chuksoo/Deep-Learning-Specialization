## Local Setup ##
To set this up on a local LaTeX setup (like `texlive`) on your own machine, you have two options:

  - **global**: plop these files into the TeX environment path (like `~/texmf/tex/latex/local/` on Linux with texlive) to make them available to any TeX project, or
  - **local**: plop them into the base directory of the project you're working on so that only it can access them.

See the `sample.tex` file for many of the features of the notebook style. The report style has similar commands, but just offers less boxes and is stylistically different.


## Online Setup ##
The difference-maker here is that platforms like Overleaf often don't support multi-file compilation. Thus, you need to instead copy-paste the `CustomCommands.sty` into the content of the note or report style (where the `\usepackage` is). Then, that whole thing needs to go into your document preamble.
