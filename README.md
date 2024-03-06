## **Applied Mathematics Notebooks**
_Welcome to the Applied Mathematics Notebooks repository!  
This collection of Google Colab notebooks covers a range of topics in applied mathematics, showcasing practical applications and implementations.     
The notebooks offer insights into applied math concepts and techniques, with a focus on fluid-dynamics/thermal simulation, machine learning, dynamical systems identification and control._

#### **Getting Started**
To get started with these notebooks, follow these steps:    
1.  Visit Google Colab page (https://colab.research.google.com/).    
2.  Click on "File" > "Open Notebook" > "GitHub".  
3.  Enter the repository URL: https://github.com/GirolamoOddo/AppliedMath_Notebooks/.    
4.  Choose a notebook to explore.  
5.  Run the notebook cells sequentially to understand and experiment with the concepts presented.

---
Notebook List:

2D_SPH_for_QuasiIncompressibleNS.ipynb
> This notebook contains a time-adaptive Smoothed Particle Hydrodynamics (SPH) solver for simulating Quasi-Incompressible Navier-Stokes equations with mirroring boundary conditions. An example of a water column released in a closed box is presented.  

2D_Solvers_for_HeatEquation.ipynb
> This notebook contains a set of numerical methods, specifically: Finite Differences, Finite Volumes, and Finite Elements to approach the solution of the heat equation in a 2D domain. The results are then compared using interactive 3D Plotly graphs. 

DeepRL_for_CruiseControl.ipynb  
> In this notebook, the application of the DDPG paradigm for continuous control with expert-learning application is presented. The proposed application is cruise control, where the agent, starting from a standstill, must reach the target speed and maintain it by acting on the throttle and brake.  
   
FNN_for_InverseStructuralProblem.ipynb
> This notebook implements a Finite Element Method (FEM) solver for solving a 2D beam problem fixed at one end and loaded at the opposite end. From this, data are extracted to solve the inverse problem using a Feedforward Neural Network (FNN), where given the maximum deformation, its position, and material properties as input, the goal is to infer the applied load.
  
PySINDy_for_ControlledSystemIdentification.ipynb
> This notebook applies the Sparse Identification of Nonlinear Dynamics (SINDY) framework to model dynamic systems with and without external control actions.  
  
RNN_for_Sequence2SequenceForecasting.ipynb
> In this notebook, various architectures of recurrent neural networks (GRU, LSTM, LMU) are implemented for modeling time-series signals, evaluating their different performances and also demonstrating applications of multi-output networks with custom losses specialized for the target.  

ResNet18_for_BinaryClassification.ipynb
> This notebook applies the ResNet network architecture to perform binary classification of images. It demonstrates how to perform preprocessing, fine-tuning, and post-processing to accomplish these tasks.  

