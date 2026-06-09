# lossmeme

A LaTeX package providing the `\Loss` command, which typesets the [Loss meme](https://cad-comic.com/comic/loss/) as a minimal TikZ figure, inline with text.


## Installation

### Manual

Copy `lossmeme.sty` to your project directory, or to a directory in your TeX path (e.g. `~/texmf/tex/latex/lossmeme/`).


## Requirements

`tikz` (part of the `pgf` bundle, included in all standard TeX distributions).

## Usage

Load the package in your preamble:

```latex
\usepackage{lossmeme}
```

Then use `\Loss` anywhere in the document body. It takes no arguments and aligns automatically to the text baseline. It also scales with the surrounding font size.

## License

[LPPL 1.3c](https://www.latex-project.org/lppl/lppl-1-3c/)
