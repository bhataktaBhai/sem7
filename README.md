# Semester 7 at IISc

I am crediting
- E0 206: Theorist's Toolkit
- E0 224: Computational Complexity Theory
- MA 231: Topology

The other 2 courses in the file tree are a relic of the past.

The code is a mess that is largely unrefactored from my first semester.
Venture into the source at your own risk.

## Compiling
I have no clue how relative paths work in LaTeX.
Change `~/IISc/sem7/` to `/path/to/this/repo/` everywhere it is used.
I compile with latexmk using the VimTeX plugin for Neovim,
but there should be no trouble with any method.
For example, `latexmk -pdf ma231.tex`.
