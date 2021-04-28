---
###
# unit information: 
# Image Enlarge 
###
title: Image Enlarge 
number: 3
short_description: Unit on cat images
summary: "This unit has the only purpouse of displaying enlarged cat images"
authors: 
- Diego Muhr
topics: [The Speculative Cat, The Exploratory Cat, The Interactive Cats]

references:

###
# page layout:
# don't change
###
layout: unit
citations: ""
mathjax: true
---

{% include unit_preamble.md %}

# Introduction

Multimedia cats need their own images.

# SPECULATIVE CATS

## How

### js & html

A small script  was added to the img-figure include, creating a modal object that takes the clicked image inside and resizes it. 

### scss

in sass/mutor a new scss file was added containing the style information. Should be transformed into the real style of the website.

### input method for images

To be able to display description as .alt and therefore as the description of the enlarged image, the img-figure method has to be used. Otherwise, if the image is entered as inline html, the alt tag has to be filled. 

A change in the begin-figure include would fix this small problem

## Examples

### Small images

This other image is quite small, only 256 × 256 px. So it resizes smaller when opening.

{% include img-figure width="350px" url="https://i.redd.it/811sizvynha51.jpg"  description="This is not a big cat" %}

### Large images

The following image is originally 2121 × 1414 px. 

{% include begin-figure description="I am quite a big cat" %}
<img width="350" alt="this was inline html, so the description is written as alt" src="https://www.rd.com/wp-content/uploads/2020/07/GettyImages-1142693329.jpg">
{% include end-figure %}

This is a 4K image: 3840 x 2160 px. 

{% include img-figure width="350px" url="https://www.wallpapersshare.com/img/big/cat-4k-wallpaper.jpg"  description="I am small cat but with LOTS fo definition" %}


{% include unit_postamble.md %}


