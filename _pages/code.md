---
layout: page
title: Code
permalink: /code/
nav: true
nav_order: 6
description:
---

This page contains Stata tools and scripts I’ve written.

---

## rround: random rounding to base 3

[`rround`](https://github.com/thomasschober/rround) is a Stata command for random rounding to the nearest multiple of 3. Useful for producing rounded, anonymised counts when 
working with confidential microdata. 


### Installation

Download the files manually:
  - [`rround.ado`](https://raw.githubusercontent.com/thomasschober/rround/main/rround.ado)
  - [`rround.sthlp`](https://raw.githubusercontent.com/thomasschober/rround/main/rround.sthlp)

Or, install the command directly from in Stata using:

```stata
net install rround, from("https://raw.githubusercontent.com/thomasschober/rround/main/")
```

### Documentation

Once installed, type `help rround` for information on the syntax and examples.