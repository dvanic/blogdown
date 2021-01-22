---
title: "Making colorblind-friendly plots in R"
author: Darya Vanichkina
date: '2020-10-02'
layout: post
slug: 2020-colorblind
tags:
  - R
---

I'm currently working on a project where all figures need to be colourblind-friendly - and we've got lots of them, with over a dozen discrete variables plotted on some. In the past, I've used the excellent [colorbrewer]() web page and [RColorBrewer]() packages to generate colour schemes, but these don't quite have built-in support for 12+ colours - so I've gone down into the depths of the stackoverflows to find out what to use. But before I dive into what I found - a digression into tools for checking a palette myself.

## How to assess and preview any palette for colourblind-friendliness?

The first tool that's now permanently in my arsenal is the [colorblindcheck]() R package, which allows one to preview any palette (supplied as a list of hex codes) in how it would be visible to someone with common types of colour blindness. 


## My 'crazy' find - the largest number of colours in a pallette

In trawling through stack overflow, I came across the following post: ["How to generate 30 distinct colors that are color-blind friendly?"](https://stackoverflow.com/questions/65013406/how-to-generate-30-distinct-colors-that-are-color-blind-friendly). That post, in turn, has a link to this [blog post](https://jacksonlab.agronomy.wisc.edu/2016/05/23/15-level-colorblind-friendly-palette/), which in turn

## Other useful links 

- [What is a “good” palette for divergent colors in R? (or: can viridis and magma be combined together?)](https://stackoverflow.com/questions/37482977/what-is-a-good-palette-for-divergent-colors-in-r-or-can-viridis-and-magma-b/52812120)
- [R color palettes for many data classes](https://stackoverflow.com/questions/9563711/r-color-palettes-for-many-data-classes/56066712)




