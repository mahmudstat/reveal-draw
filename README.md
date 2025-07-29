# reveal-draw

Allows drawing and erasing in a revealjs presentation rendered via quarto

## Installation

Installation is a cakewalk. Just download the file `drawing-tools.html` and make sure it resides on the same folder as you `qmd` file. Then add the file in `yml` header in the following way:

```
---
title: "Drawing Tools"
format:
  revealjs:
    include-in-header: drawing-tools.html
---
```

## Usage

Add you contents to `qmd` file and render.

## Demo

You can see a demo [here](https://docs.statmania.info/slide/02-random-variable.html). You can also downlaod and run the `qmd` file on this repository.
