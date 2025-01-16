This repository contains the python files required to make my manim thesis presentation. 
Below are the steps for installing and rendering the presentation on your local PC!

## Installing Manim

Install manim using the steps outlined [here][https://docs.manim.community/en/stable/installation.html#conda-installation].

## Installing Manim Slides

Install manim slides using the steps outlined [here][https://www.manim.community/plugin/manim-slides/#installation].

## Learn!

Learn about manim [here][https://docs.manim.community/en/stable/tutorials/quickstart.html] and manim-slides [here][https://manim-slides.eertmans.be/latest/] and [here][https://www.manim.community/plugin/manim-slides/].

## Compile the files

There are two steps to compile:

### Rendering

This step is done by executing the command: `manim-slides render {filename}.py {classname}` where `{filename}` is the name of the python file and `{classname}` is the main of the main class inside it.
For example, you can write the command `manim-slides render galois.py Galois`, and you have to do so for every file.

### Converting

Suppose you want to have the slides include "Class1" "Class2" "Class3" in that order, so you execute the command `manim-slides convert Class1 Class2 Class3`.
For example, in this repo, you should write `manim-slides convert Intro Vectors Matrix Matrix2 LinearText Galois`.
