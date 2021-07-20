# How to learn modern Compressive Sensing
A guide to the intrepid adventurer.

## Description

Compressive Sensing are methods that were developed in the last 15 years (post. 2000). They are really interesting methods and a subject that is not only pure mathematics because it has many applications in many fields of engineering. In this small guide I will list good resources to learn Compressive Sensing in a fun and enjoyable way. <br>

## Compressive Sensing

How to use only a small part of the data and still be able to reconstruct an image. For example in a image, how to use only a small group of pixels and reconstruct the all image. <br>


1. **Video - Compressed Sensing: Overview** <br>
   [https://www.youtube.com/watch?v=SbU1pahbbkc](https://www.youtube.com/watch?v=SbU1pahbbkc)

2. **Video - Compressed Sensing: Mathematical Formulation** <br>
   [https://www.youtube.com/watch?v=inr-nGnVc0k](https://www.youtube.com/watch?v=inr-nGnVc0k)

3. **Video - Compressed Sensing: When It Works** <br>
   [https://www.youtube.com/watch?v=hmBTACBGWJs](https://www.youtube.com/watch?v=hmBTACBGWJs)

4. **Video - Sparsity and the L1 Norm** <br>
   [https://www.youtube.com/watch?v=76B5cMEZA4Y](https://www.youtube.com/watch?v=76B5cMEZA4Y)

5. **Video - Underdetermined systems and compressed sensing - Matlab** <br>
   [https://www.youtube.com/watch?v=otr1YwNBWfc](https://www.youtube.com/watch?v=otr1YwNBWfc)

6. **Video - Underdetermined systems and compressed sensing - Python** <br>
   [https://www.youtube.com/watch?v=_-Jkq-Faa2Y](https://www.youtube.com/watch?v=_-Jkq-Faa2Y)


## Compressive Sensing and the Nyquist Sampling Theorem

The Nyquist sampling theorem, says that we need to sample at two times the maximum frequency of the signal to have a complete reconstruction of the signal. But with Compressive Sensing we could have a much lower sample rate (number of samples by unit of time) condition to the fact that the sampling is random in time or space and that we know the sampled clock with some precision. For example, in a audio signal of two tones we can reconstruct with a sample rate that is 32x below the Nyquist sample rate and still reconstruct the signal. <br>


1. **Video - Shannon Nyquist Sampling Theorem** <br>
   [https://www.youtube.com/watch?v=FcXZ28BX-xE](https://www.youtube.com/watch?v=FcXZ28BX-xE)

2. **Video - Beating Nyquist with Compressed Sensing, in Python** <br>
   [https://www.youtube.com/watch?v=5-LY6wBIKx8](https://www.youtube.com/watch?v=5-LY6wBIKx8)

3. **Video - Beating Nyquist with Compressed Sensing in Matlab** <br>
   [https://www.youtube.com/watch?v=A8W1I3mtjp8](https://www.youtube.com/watch?v=A8W1I3mtjp8)

4. **Video - Beating Nyquist with Compressed Sensing in Matlab, part 2** <br>
   [https://www.youtube.com/watch?v=HVR2DaaD0Xo](https://www.youtube.com/watch?v=HVR2DaaD0Xo)


## Tailored Sensing

Imagine that you will have to place sensors in some physical way along an area (ex: the ocean or in a airfoil) to obtain data from a physical phenomenon. You couldn’t spread sensors in all the area, so you had to choose carefully a way of placing the least possible sensors in a way that maximized the reconstruction fidelity of the underling phenomenal if you had some examples of samples of a model of that  phenomenon. The same  can be applied to many other fields, for example to images in that you could reconstruct images, or detect images from only a small set of pixels. <br>


1. **Video - Sparse Sensor Placement Optimization for Reconstruction** <br>
   [https://www.youtube.com/watch?v=BCygBhyrl8k](https://www.youtube.com/watch?v=BCygBhyrl8k)

2. **Video - Sparse Sensor Placement Optimization for Classification** <br>
   [https://www.youtube.com/watch?v=zJ2z__5mepA](https://www.youtube.com/watch?v=zJ2z__5mepA)


## Free Book related to the videos:

1. **Book site** <br>
   [http://databookuw.com/](http://databookuw.com/)

2. **Free book from the author of the above youtube channel** <br>
   [http://databookuw.com/databook.pdf](http://databookuw.com/databook.pdf)


## Other good sources on Compressive Sensing

1. **Compressive Sensing – A 25 Minute Tour** <br>
   Emmanuel Candès <br>
   [https://www.raeng.org.uk/publications/other/candes-presentation-frontiers-of-engineering](https://www.raeng.org.uk/publications/other/candes-presentation-frontiers-of-engineering)

2. **A Systematic Review of Compressive Sensing: Concepts, Implementations and Applications** <br>
   Meenu Rani,S. B. Dhok, and R. B. Deshmukh <br>
   [https://ieeexplore.ieee.org/document/8260873](https://ieeexplore.ieee.org/document/8260873)

Article that has a historical vision of Compressive Sensing and info about the performance and complexity of the different algorithms used in the field. <br> 

3. **Reconstruction Algorithms in Compressive Sensing: An Overview** <br>
   by André Luiz Pilastri, João Manuel R. S. Tavares <br>
   [https://sigarra.up.pt/faup/pt/pub_geral.pub_view?pi_pub_base_id=139664](https://sigarra.up.pt/faup/pt/pub_geral.pub_view?pi_pub_base_id=139664)


## COSAMP method / algorithm - Compressive Sensing by matching pursuit

Simple and fast algorithm used in the optimization phase of compressed sensing (minimization with constrains). <br>

1. Paper <br> 
   **CoSaMP: Iterative signal recovery from incomplete and inaccurate samples** <br>
   [https://www.sciencedirect.com/science/article/pii/S1063520308000638](https://www.sciencedirect.com/science/article/pii/S1063520308000638)

2. **Cosamp Github implementation** <br>
   [https://github.com/avirmaux/CoSaMP](https://github.com/avirmaux/CoSaMP)


# Mathematical background info

The following are some really good books in each subject, the majority which is free and the one that aren’t are low cost. This books will help you understand the underling mathematics. <br>


## Good book on Linear Algebra

1. **Linear Algebra: Theory, Intuition, Code** <br>
   by Mike X Cohen

## Good book on mathematical optimization - minimization of functions based on constrains

1. **Algorithms for Optimization - The MIT Press** <br>
   by Mykel J. Kochenderfer

* **Free book on the tab download** <br>
  [https://algorithmsbook.com/optimization/](https://algorithmsbook.com/optimization/)

2. **Convex Optimization** <br>
   by Stephen Boyd, Lieven Vandenberghe

* **Free book online** <br>
  [https://web.stanford.edu/~boyd/cvxbook/](https://web.stanford.edu/~boyd/cvxbook/)


## Good book on Probability and Statistics

1. **Introduction to Probability, Statistics, and Random Processes** <br>
   by Hossein Pishro-Nik

* **Free book online** <br>
  [https://www.probabilitycourse.com/](https://www.probabilitycourse.com/)


## Good book on Information Theory

1. **Information Theory, Inference and Learning Algorithms** <br>
   by David J. C. MacKay

* **Free book online** <br>
  [https://www.inference.org.uk/itprnn/book.pdf](https://www.inference.org.uk/itprnn/book.pdf)

* **Site** <br>
  [https://www.inference.org.uk/itprnn/](https://www.inference.org.uk/itprnn/)


## Good book on general Engineering Mathematics

1. **Engineering Mathematics** <br>
   by Prof Anthony Croft, Dr Robert Davison, James Flint, Martin Hargreaves


# All my other guides

* The links to all my guides are in: <br>
  **Guides on Linux - Programming - Embedded - Electronics - Aeronautics** <br>
  [https://github.com/joaocarvalhoopen/Guides_Linux-Programming-Electronics-Aeronautics](https://github.com/joaocarvalhoopen/Guides_Linux-Programming-Electronics-Aeronautics)


# Have fun!

Best regards, <br>
Joao Nuno Carvalho
