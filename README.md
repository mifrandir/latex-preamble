# LaTeX Preamble
The LaTeX preambles I use for most of my university work.

I do most of my work in LaTeX documents and thus I need a lot of preambles. Since
there are only few variations, I thought it was about time that I merged them together.

There are three relevant files:

- [preamble.sty](./preamble.sty) contains most of the packages and utilities
- [notes-preamble.py](./notes-preamble.py) contains some changes specifically for course notes
- [homework-preamble.py](./homework-preamble.py) contains some changes specifically for hand-ins and homeworks

## Installation

Clone the repository

```
$ git clone https://github.com/miltfra/latex-preamble
```

Then you can copy the desired `.sty` files directly into the directory with your `.tex` files or you follow [these](https://tex.stackexchange.com/questions/278817/creating-a-default-preamble) [guides](https://tex.stackexchange.com/questions/1137/where-do-i-place-my-own-sty-or-cls-files-to-make-them-available-to-all-my-te) to make the package available everywhere.


## Usage

Just put

```latex
\usepackage{preamble}
```

at the beginning of your document. Then you can use all the features as you'd expect.
