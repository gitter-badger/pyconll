## pyconll

A simple package with simple intentions. Easily manipulate conll files using the familiar syntax of python.


## Motivation

When working with the Universal Dependencies project, I was dissapointed with the lack of good API options for maniuplating the conll files. There are plenty of good tools, none of which are general purpose enough. Grew is a great tool, but I found was slightly limiting for some tasks (and extremely productive for others). Treex is similar to grew in this regard. CL-CoNLLU is essentailly what I need, but it written in a language that many are not familiar with, Lisp. UDAPI might fit the bill, but it takes a while to go through the documentation and the package itself is quite large. More tools can be found on the Universal Dependencies page, but I found that all of them were lacking for my usage pattern. Namely, conll file manipulation in python in a simple, and intuitive way. This is my attempt at a small, intuitive package in a popular language that can be used in complex systems or small one off scripts.


## Install

Installation is easy like with most python packages. Simply use `pip` to install from PyPi.

```
pip install pyconll
```

This package is designed for, and only tested with python 3.4 and above.