### Slow Feature Analysis

Repository created to collect my work for the project "Slow Feature Analysis", as a part of the Fundamentals of Computer Science for Neuroengineering course at TUM. 

-----

#### What is SFA?

SFA (Slow Feature Analysis) is an unsupervised learning algorithm for extracting slowly varying features from a quickly varying input signal. In Computational Neuroscience, SFA can be applied to attempt an understanding of how the brain learns to form meaningful representations of its environment (whose appearance changes mostly in a continuous way over time) from statistical regularities in the sensory input (for example, the responses of individual retinal receptors that vary on a faster scale). 

#### About the project

This project aims at the implementation of the SFA algorithm in Python. Firstly, I will focus on linear SFA transformations on a 2-dimensional time-dependent signal. Secondly, I will use linear SFA on a high-dimentional correlated signal, simulating a slowly moving input to the receptive of a hypothetical visual cell.

#### Results

![Slowest eigenvectors](https://github.com/fulviadelduca/slow-feature-analysis/blob/master/Figures/slowest_eigv.jpg)
Here, we can see how the shape of the first five eigenvectors (plotted against the pixels of the receptive field) corresponds to the core concept of SFA: the slowness of these components is reflected in the frequency of the sinusoidal. Thus, the five slowest eigenvectors represent the slowest varying features because they are varying slowly over the range of the receptive field.

![Five slowest and fastest components](https://github.com/fulviadelduca/slow-feature-analysis/blob/master/Figures/final_plot.jpg)
Here, the five slowest components of the signal in the SFA basis are plotted, compared to the five fastest components. We can clearly see how the slowness decreases among the components.
