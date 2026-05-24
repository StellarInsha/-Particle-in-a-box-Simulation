# -Particle-in-a-box-Simulation

# Particle in a Box Visualization

One of the strangest things about quantum mechanics is that particles do not always behave like teeny tiny balls. Sometimes, they behave more like waves.

This project explores that idea through one of the most fundamental problems in quantum mechanics: the particle in an infinite potential well, also called the “particle in a box”

Using Python, I have tried to visualize how quantum wavefunctions behave, how probability appears, and why energy becomes quantized when a particle is confined.


# The Idea

Imagine a guitar string fixed at both ends.

The string cannot vibrate in just any random way cause only certain standing wave patterns fit properly between the edge boundaries.

A quantum particle situated inside a box behaves similarly.

The walls force the wavefunction to become zero at the boundaries, and because of this, only specific wave patterns are allowed. These allowed patterns correspond to specific energy states only.

So, there is quantization of things.


# What This Project Visualizes



1. Wavefunctions
   The project first plots the stationary-state wavefunctions for different quantum numbers.

    As the quantum number increases:

    * the number of oscillations increases
    * more nodes appear
    * and the wave becomes more tightly packed



2. Probability Density

   In quantum mechanics, the wavefunction itself is not directly observable.

   What we can measure is:

   psi(x) squared

   which represents the probability density of finding the particle at a particular position.

  

3. Quantized Energy Levels

   The project also helps us see the different energy levels that a particle can have. (Unlike classical mechanics it has fixed/discrete energy values which particle can obtain)

  

   That discreteness emerges naturally from the wave nature of the system.


4. Interactive Exploration

   I also created an interactive notebook using sliders for:

   * quantum number (n)
   * box length (L)

  by uisng of which, the system can be explored dynamically instead of only through static plots.

Changing these parameters in real time helps to understand how confinement affects the wave behavior of the particle.



# Tools Used

 * Python
 * NumPy
 * Matplotlib
 * ipywidgets
 * Jupyter Notebook



# Why I Made This

I was going through introductory quantum mechanics using Griffiths, and I wanted to do more than just solve problems with symbols. I wanted to connect the math to visualizations and computations, to really see what's going on and so I built this.
























Here, I have made an inbteractive simulation of probability density of Particle in a Box:
https://colab.research.google.com/drive/1-cr3iCAvNYUWAiTX3JYprqwq3cJCAaO6?usp=sharing
