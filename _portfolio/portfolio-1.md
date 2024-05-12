---
title: "Predicting Aggregation Properties in a Self-Assembling System"
excerpt: "For ChE 4220, Data Science in Chemical Engineering, we were tasked with a final project using the techniques we covered in the class to explore a dataset of our choice." 
collection: portfolio
---

For ChE 4220, Data Science in Chemical Engineering, we were tasked with a final project using the techniques we covered in the class to explore a dataset of our choice. 

[Project Here](https://github.com/mohan-s1/lammps_work/blob/9793506a89e6bf689115417e5d5304fb69332e11/che_for_ds_final_project.ipynb)

## General Description 

The GEM-n potential is defined as 
$$
\phi (r) = \varepsilon e^{- \left( \frac{r}{\sigma} \right)^n} 
$$
which is of interest since the system will undergo clustering if n > 2 solely through repulsive interactions. Using the OVITO Python library, the `cluster analysis` feature was used to create the dataset from LAMMPS trajectory files before SciKit Learn implementations of regression techniques like Kernel Ridge and Gaussian Process were implemented to make predictions about the data. Furthermore, a simple classification model was setup where kNN, Decision Tree, and SVM was used to solve the problem.
