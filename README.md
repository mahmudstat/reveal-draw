# reveal-draw

Allows drawing and erasing in a revealjs presentation rendered via quarto

## Installation

- Download the [latest release](https://github.com/mahmudstat/reveal-draw/releases/) or simply `drawing-tools.html`
- Put `drawing-tools.html` in the same directory as your `qmd` slide (if you just dowloade the `html`)
- Use the following in `yml`

```
---
title: "Drawing Tools"
format:
  revealjs:
    include-in-header: drawing-tools.html
---
```

## Usage

- Add you contents to `qmd` file and render.

- Click on the draw icon 🎨 to activate the drawing tools. Click the icon again to hide the tools.

## Demo

You can see a matured demo [here](https://docs.statmania.info/slide/02-random-variable.html) and a [minimal demo here](https://www.thinkermahmud.com/reveal-draw/). You can also downlaod and run the `qmd` file on this repository.

## Customization

You can easily change the icon style and behavior by editing the `drawing-tools.html` file.

## Advanced Usage

If you have many slides residing in the same folder, you can add the tool in your _output.yml and it would apply to all the slides in the directory.
