# LaTeX Preamble
The LaTeX preambles I use for most of my university work.

I do most of my work in LaTeX documents and thus I need a lot of preambles. Since
there are only few variations, I thought it was about time that I merged them together.

There are three relevant files:

- [preamble.sty](./preamble.sty) contains most of the packages and utilities
- [notes-preamble.py](./notes-preamble.py) contains some changes specifically for course notes
- [homework-preamble.py](./homework-preamble.py) contains some changes specifically for hand-ins and homeworks

## Usage

Just put

```latex
\usepackage{preamble}
```

at the beginning of your document. Then you can use all the features as you'd expect.