---
layout: page
title: Code
permalink: /code/
---

# Code

This page contains Stata tools and scripts I’ve written.

---

## rround: Random rounding to base 3

[`rround`](https://github.com/thomasschober/rround) is a Stata command for random rounding to the nearest multiple of 3. Useful for producing rounded, anonymised counts when 
working with confidential microdata. 


### Installation

Download the files manually from the GitHub repository:
  - [`rround.ado`](https://github.com/thomasschober/rround/blob/main/rround.ado)
  - [`rround.sthlp`](https://github.com/thomasschober/rround/blob/main/rround.sthlp)

Or, install the command directly from GitHub into Stata using:

```stata
net install rround, from("https://raw.githubusercontent.com/thomasschober/rround/main/")
```

### Documentation

Once installed, type
```stata
help rround
```
for information on the syntax and examples.