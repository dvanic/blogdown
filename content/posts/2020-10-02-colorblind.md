---
title: "Making colorblind-friendly plots in R"
author: Darya Vanichkina
date: '2020-10-02'
layout: post
slug: 2020-colorblind
tags:
  - R
---

I'm currently working on a project where all figures need to be colourblind-friendly - and we've got lots of them, with over a dozen discrete variables plotted on some. In the past, I've used the excellent [colorbrewer]() web page and [RColorBrewer]() packages to generate colour schemes, but these don't quite have built-in support for 12+ (12?!?!?) colours - so I've gone down into the depths of the stackoverflows to find out what to use.

## How to assess and preview any palette for colourblind-friendliness?

The first tool that's now permanently in my arsenal is the [colorblindcheck]() R package, which allows one to preview any palette (supplied as a list of hex codes) to 





