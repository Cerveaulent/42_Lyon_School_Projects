# 42 Lyon School Projects

This repository is an overview of my projects at 42 Lyon school. Most of them are in C language.
These projects were coded on MacOs, but I tried to ensure Linux compatibility when I could.

# Projects rules

All those projects have the same structure :

* an autor file (deprecated)
* a Makefile
* includes folder
* source folder
* library folders if needed

Every project must be written following a **strict norm**, ( [Eng](https://github.com/Cerveaulent/42_Lyon_School_Projects/blob/master/norm/norme.en.pdf), [Fr](https://github.com/Cerveaulent/42_Lyon_School_Projects/blob/master/norm/norme.fr.pdf) ) and have prohibited functions and/or libraries.

***Memory leaks are forbidden in all projects.***
***Programs shouldn't quit unexpectedly.***

Graphical projects  ***FDF*** and ***fractol*** are using the **Minilibx** graphical library (aka MLX), developed by Ol (Olivier Crouzet) for 42 schools. MLX exists under two versions : a MacOs only and one for Linux. Both projects have both sources, making them runnable on both OS (but work best on MacOs). ***MLX for Linux isn't well ported***, so you might need to find a workaround to compile/run the projects.

***Rushes*** follow their specific rules, and are marked with ***(Rush)*** tag in the following sections.

More details can be found in each project guidelines pdf.

# Projects

##  1 . Libft : 

<h4> Description : 

###
  
  *A simple library to use in projects, **re-writing some of C standard functions**, in order to understand how they work and how to use them. I added some functions that I used in my other projects during my cursus.*
  
###
  
* [GitHub Project Page](https://github.com/Cerveaulent/Libft/blob/master/README.md)

* Project Guidelines :  [Eng](https://github.com/Cerveaulent/Libft/blob/83072955a711f058f9fd51fb1f49ac21de476297/subjects/libft.en.pdf)   [Fr](https://github.com/Cerveaulent/Libft/blob/83072955a711f058f9fd51fb1f49ac21de476297/subjects/libft.fr.pdf)

## 2 . GNL :

<h4> Description : 
  
###
  
  *A simple function that allows you to read one line from a file.*
  *The goal is to learn how to use **file descriptors**,  **malloc()**, **read()**, **open()**, **close()** functions, and our **libft** library.*
  
###

* [GitHub Project Page](https://github.com/Cerveaulent/GNL/blob/master/README.md)

* Project Guidelines :  [Eng](https://github.com/Cerveaulent/GNL/blob/e4339de7e288276e5a1cdbc9c71418a40b4a55d8/subjects/get_next_line.en.pdf)   [Fr](https://github.com/Cerveaulent/GNL/blob/e4339de7e288276e5a1cdbc9c71418a40b4a55d8/subjects/get_next_line.pdf)

## 3 . Fillit :

<h4> Description : 
  
###
  
  *An **algorithm** to assemble a given **Tetriminos set** altogether in the **smallest possible square**. Tetriminos are 4-blocks geometric figures from the game **Tetris**.*
  *The goal is to familiarize ourselves with recurrence problematic in programming.*
  
###

* [GitHub Project Page](https://github.com/Cerveaulent/Fillit/blob/master/README.md)

* Project Guidelines :  [Eng](https://github.com/Cerveaulent/Fillit/blob/e3a431d8f3ff669dbac3d4e005860965ecc61023/subjects/fillit.en.pdf)   [Fr](https://github.com/Cerveaulent/Fillit/blob/e3a431d8f3ff669dbac3d4e005860965ecc61023/subjects/fillit.fr.pdf)

## 4 . FDF :

<h4> Description : 
  
###
  
  ![FDF](https://github.com/Cerveaulent/42_Lyon_School_Projects/blob/master/screenshots/screen_fdf.png)
  
  *A program that computes a simple topographic map (a text file where numbers represent the height of a given point)  and represents it in **a wireframe isometric projection**. The goal is to discover **the basics of graphic programming** and to use **miniLibX graphic** library*
  
###

* [GitHub Project Page](https://github.com/Cerveaulent/FDF/blob/master/README.md)

* Project Guidelines :  [Eng](https://github.com/Cerveaulent/FDF/blob/bceedc8b1604b0816c2e2d3a1245975dfe028fd6/subjects/fdf.en.pdf)   [Fr](https://github.com/Cerveaulent/FDF/blob/bceedc8b1604b0816c2e2d3a1245975dfe028fd6/subjects/fdf.fr.pdf)

## 5 . Fract_ol :

<h4> Description : 
  
###
  
  ![Mandelbrot](https://github.com/Cerveaulent/42_Lyon_School_Projects/blob/master/screenshots/Screenshot%20from%202020-05-17%2018-04-20.png)
  
  *A program that computes **fractals** :*
  * Mandelbrot [eng](https://en.wikipedia.org/wiki/Mandelbrot_set) - [fr](https://fr.wikipedia.org/wiki/Ensemble_de_Mandelbrot), 
  * Julia [eng](https://en.wikipedia.org/wiki/Julia_set) - [fr](https://fr.wikipedia.org/wiki/Ensemble_de_Julia), 
  * Burning ship [eng](https://en.wikipedia.org/wiki/Burning_Ship_fractal) - [fr](https://fr.wikipedia.org/wiki/Fractale_burning_ship)
   
  *and represents them with **different color schemes**. Julia's set has a special feature that allows you to make its parameter vary whilst moving the mouse. The goal is discover/use the notion of **complex numbers**, and have a good insight of **optimization problems**.*
 
###

* [GitHub Project Page](https://github.com/Cerveaulent/fractol/blob/master/README.md)

* Project's Guidelines :  [Eng](https://github.com/Cerveaulent/fractol/blob/5871f028836db33dcde22ae43c82c7fd649b4307/subjects/fract_ol.en.pdf)   [Fr](https://github.com/Cerveaulent/fractol/blob/5871f028836db33dcde22ae43c82c7fd649b4307/subjects/fract_ol.fr.pdf)

## 6 . ft_ls :

<h4> Description : 
  
###
  
  *An implementation of the **ls POSIX command**. The goal is to learn how to properly **manage data structures**, **files** and **directories** and to **discover Unix API**.*
  
  <h6> Isn't compatible with Linux distros
  
###

* [GitHub Project Page](https://github.com/Cerveaulent/ft_ls/blob/master/README.md)

* Project Guidelines :  [Eng](https://github.com/Cerveaulent/ft_ls/blob/e679c5dc9d9ca3b92f7b98819afa4f3e3ae72580/subjects/ft_ls.en.pdf)   [Fr](https://github.com/Cerveaulent/ft_ls/blob/e679c5dc9d9ca3b92f7b98819afa4f3e3ae72580/subjects/ft_ls.pdf)

## 7 . (Rush) MiniRogue :

<h4> Description : 
  
###
  
  *An implementation of [Rogue game](https://en.wikipedia.org/wiki/Roguelike) in Python language within limited time (48 hours)*
  
###

* [GitHub Project Page](https://github.com/Cerveaulent/Rush_MiniRogue/blob/master/README.md)

* Project Guidelines :  ~~[Eng]()~~  [Fr](https://github.com/Cerveaulent/Rush_MiniRogue/blob/c39804864a69ca8b34eb449b19458bef3dccba97/subjects/ft_minirogue.pdf)
