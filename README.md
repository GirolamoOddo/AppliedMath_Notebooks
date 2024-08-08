
![photo1709798867](https://github.com/GirolamoOddo/AppliedMath_Notebooks/assets/101062431/395d8eeb-85fa-473c-95c9-6c9db31c6d64)



## **Applied Mathematics Notebooks**
_Welcome to the Applied Mathematics Notebooks repository!  
This collection of Google Colab notebooks covers a range of topics in applied mathematics, showcasing practical applications and implementations.     
The notebooks offer insights into concepts and techniques on numerical simulation, machine learning, dynamical systems identification, optimization and control._

#### **Getting Started**
To get started with these notebooks, follow these steps:    
1.  Visit Google Colab page (https://colab.research.google.com/).    
2.  Click on "File" > "Open Notebook" > "GitHub".  
3.  Enter the repository URL: https://github.com/GirolamoOddo/AppliedMath_Notebooks/.    
4.  Choose a notebook to explore.  
5.  Run the notebook cells sequentially to understand and experiment with the concepts presented.

NOTES: All Notebooks works with Python 3.10.12, to downgrade to this version use:  
```
!apt-get install python3.10
!ln -sf /usr/bin/python3.10 /usr/bin/python
```  
check COLAB_VERSION file for further information on Colab Notebook version.  
  
---
#### **Notebooks List**
Numerical Simulation: 🟧, 
Machine learning / Dynamical systems identification: 🟩, 
Optimization / Control: 🟦.  

2D_SPH_for_QuasiIncompressibleNS.ipynb [🟧]  
> This notebook contains a time-adaptive Smoothed Particle Hydrodynamics (SPH) solver for simulating Quasi-Incompressible Navier-Stokes equations with mirroring boundary conditions. An example of a water column released in a closed box is presented.  

2D_Solvers_for_HeatEquation.ipynb [🟧]  
> This notebook contains a set of numerical methods, specifically: Finite Differences, Finite Volumes and Physics Informed Covolutional NN to approach the solution of the heat equation in a 2D domain. The results are then compared using interactive 3D Plotly graphs.

AdversarialSearch_for_ZeroSumScenario.ipynb [🟦]    
>This notebook aims to provide a practical insight into adversarial search through the use of the Minimax algorithm applied to a simple two-player game (user vs. algorithm) with complete information and zero-sum property.

AoAOptimization_for_GroundEffectAirfoil.ipynb [🟦]    
> In this notebook, it will be presented, through a practical example, how to proceed with the optimization of a convex problem using SciPy. Specifically, the application to the case of a symmetric airfoil profile, NACA 0012, under ground effect conditions will be demonstrated. The aim is to find, at different heights from the ground, the angle of attack that maximizes the efficiency of the profile.

DeepRL_for_CruiseControl.ipynb [🟩 🟦]      
> In this notebook, the application of the DDPG paradigm for continuous control with expert-learning application is presented. The proposed application is cruise control, where the agent, starting from a standstill, must reach the target speed and maintain it by acting on the throttle and brake.  
   
FNN_for_InverseStructuralProblem.ipynb [🟧 🟩]
> This notebook implements a Finite Element Method (FEM) solver for solving a 2D beam problem fixed at one end and loaded at the opposite end. From this, data are extracted to solve the inverse problem using a Feedforward Neural Network (FNN), where given the maximum deformation, its position, and material properties as input, the goal is to infer the applied load.

MultiLevelMonteCarlo_for_ParameterEstimation.ipynb [🟩]  
> This notebook aims to estimate the damping coefficient of a mass-spring-damper system using Monte Carlo and Multi-Level Monte Carlo methods. From these, considerations will also be drawn regarding the efficiency of the method by comparing the obtained results.
  
PySINDy_for_ControlledSystemIdentification.ipynb [🟩 🟦]    
> This notebook applies the Sparse Identification of Nonlinear Dynamics (SINDY) framework to model dynamic systems with and without external control actions.  
  
RNN_for_Sequence2SequenceForecasting.ipynb [🟩]  
> In this notebook, various architectures of recurrent neural networks (GRU, LSTM, LMU) are implemented for modeling time-series signals, evaluating their different performances and also demonstrating applications of multi-output networks with custom losses specialized for the target.  

ResNet18_for_BinaryClassification.ipynb [🟩]  
> This notebook applies the ResNet network architecture to perform binary classification of images. It demonstrates how to perform preprocessing, fine-tuning, and post-processing to accomplish these tasks.  

SympleticIntegration_for_MassSpringSystem.ipynb [🟧]  
> This notebook explores symplectic/geometric numerical integration and compares it with its non-symplectic counterpart of the same order. The proposed application case is the analysis of a spring-mass system using the Verlet and Runge-Kutta 2 methods.

SystemIdentification_for_DiscreteMarkovProcesses.ipynb [🟩 🟦]    
>In this notebook, Markov processes are explored and it is shown how it is possible to estimate the transition probability matrix with different estimation techniques, Maximum Likelihood (MLE) and Wavelet Based Maximum Likelihood (WMLE). A Markov Decision Process problem is also presented, focusing on a maintenance management case, identifying the optimal control policy.
  
---
#### **Citation Format**

To cite this work, please use the following BibTeX entry:  

>@misc{GirolamoOddo.2024,  
  author = {Girolamo Oddo},  
  title = {AppliedMath_Notebooks: Notebook Title},  
  year = {2024},  
  publisher = {GitHub},  
  journal = {GitHub repository},  
  howpublished = {\url{https://github.com/GirolamoOddo/AppliedMath_Notebooks.git}},  
}

---
#### **Acknowledgements**

This collection mainly stems from insights for further study provided to me by Dr. Roberto Nuca from the Advanced Algorithm and Numerical Simulation Lab at KAUST, during my time visiting their laboratory.  
I would therefore like to thank him for the extensive overview he provided me on the world of applied mathematics and numerical simulation.
