# **Quasi-Particle Mass Prediction Using Deep Neural Networks**

Team Members
Joshua Bickers,  
Jean Guma De La Vega,  
Ricardo Lopez

## **Introduction**
This project explores the prediction of quasi-particle masses in the quark-gluon plasma (QGP) state using machine learning techniques, specifically deep neural networks (DNN). QGP is a high-energy state of matter where quarks and gluons, the building blocks of protons and neutrons, move freely. Understanding its properties, such as pressure, energy density, and entropy, is crucial in theoretical physics. Traditional methods, while accurate, are computationally intensive and difficult to scale. This project demonstrates how DNNs can provide a more efficient alternative.

## **Acknowledgments**
We acknowledge the HotQCD and WB Lattice groups for providing the datasets. Special thanks to Dr. Zak and our colleagues for their guidance.

Dependencies:
Python 3.10,  
TensorFlow,  
Pandas,  
Matplotlib,  
NumPy,  

The dataset consists of the following features:
Temperature (T),  
Pressure (P),  
Energy Density (ε),  
Entropy Density (s),  
Trace Anomaly (D),  

## **Results**
The DNN model demonstrates acceptable accuracy, especially at lower temperature ranges. However, divergence occurs at higher temperatures due to limited dataset size and the complexity of QGP properties.
Model outputs are visualized, comparing predictions with true values.

## **References**
- [Deep-learning quasi-particle masses from QCD equation of State](https://arxiv.org/abs/2211.07994)
