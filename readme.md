A system of "tone-letters" (Chao 1930)
======================================

This repository hosts the Chao 1930 paper entitled 'A system of "tone-letters"'
typeset in ordinary English orthography by [Jackson Lee](http://jacksonllee.com/):

- PDF: [`chao1930.pdf`](chao1930.pdf)
- LaTeX source code: [`chao1930.tex`](chao1930.tex)

To compile the ``.tex`` (assuming you are at this directory on the command line):

```
$ latex chao1930.tex
$ dvipdf chao1930.dvi
```

A scan of the original paper (written in IPA) is also available:
[`chao1930-original.pdf`](chao1930-original.pdf)

Change log
----------

- September 2016

  Differentiate the two kinds of "tone letters", one with the reference bars
on the *right* (as implemented in vanilla LaTeX ``tipa``) and the other with the
reference bars on the *left*
(as used for English intonation, page 26 of Chao 1930,
and the Tibetan illustration, page 27). Thanks to Alexis Michaud for
pointing out the differences.

- July 2015

  First version

