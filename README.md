# McMaster Kinesiology xaringan theme
A minimalist xaringan theme for html presentations using McMaster University brand/colors. The theme is built off of the Arkansas State theme, which was built off the Rutgers theme. This theme uses McMaster's Heritage brand colors in most places and some Brighter World colors are also included.

## Demo
TODO

## Usage
Download or clone repository. Copy the `mackin.css` and `mackin-fonts.css` files from the `css/` directory to your `xaringan` distribution. You can use the YAML header below to create your presentation or you can use the `index.Rmd` file in the `slides/` directory as a starting point.

```
title: "Your catchy title"
subtitle: "Your unncessary subtitle"
author: "Your name"
date: "McMaster University </br> `r Sys.Date()`"
output:
  xaringan::moon_reader:
    lib_dir: libs
    css: ["mackin", "mackin-fonts"]
    nature:
      beforeInit: ["../js/mackin-xaringan.js"]
      highlightStyle: github
      highlightLines: true
      countIncrementalSlides: false
      ratio: "16:9"
```
