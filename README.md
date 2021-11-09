# Félix Fernández - Master's Thesis - Deep Learning for simulation of physical systems.

This repository stores both the code and the text belonging to the Master's Degree in Data Science I studied in the University of Granada during the course 2020/21. 
The thesis' main theme was physics simulations through neural networks.

For this project, I first learned about some the Deep Learning techniques currently available for building physics regression models, 
focusing on PINNs (Physics-Informed Neural Networks). 
After this documentation stage, I wrote a short introductory text about the process of creating physics models (available in Chapter 2 of [the text](https://github.com/felixfdlm/deepsim-PINN-Experimentation/blob/main/Felix%20Fernandez%20de%20la%20Mata%20-%20TFM%20-%20Deep%20Learning%20para%20la%20simulacion%20de%20sistemas%20fisicos.pdf)), 
explaining some of the main points, such as differential equations, classic techniques and deep learning-based techniques.

Secondly, I evaluated the proficiency of PINNs when building regression models in comparison to a more widespread method, the FEM (Finite Elements Method). 
To do so, I coded 3 experimentation loops of increasing complexity: [Experimento Barra](https://github.com/felixfdlm/deepsim-PINN-Experimentation/tree/main/Experimento%20Barra), 
[Experimento Placa](https://github.com/felixfdlm/deepsim-PINN-Experimentation/tree/main/Experimento%20Placa) and 
[Experimento Cubo](https://github.com/felixfdlm/deepsim-PINN-Experimentation/tree/main/Experimento%20Cubo), each of them divided in two stages. On each of these loops,
a considerable amount of PINNs were trained using varying different parameters, and later evaluated against FEM-generated data. The outcomes of these experiments are
further discussed on [Chapter 4](https://github.com/felixfdlm/deepsim-PINN-Experimentation/blob/main/Felix%20Fernandez%20de%20la%20Mata%20-%20TFM%20-%20Deep%20Learning%20para%20la%20simulacion%20de%20sistemas%20fisicos.pdf).

Lastly, I coded a [showcase experimentation](https://github.com/felixfdlm/deepsim-PINN-Experimentation/tree/main/Experimento%20Flujo), 
in which I tried to train a PINN to solve a complex problem (related to fluid mechanics). Results are also dicussed on [Chapter 4](https://github.com/felixfdlm/deepsim-PINN-Experimentation/blob/main/Felix%20Fernandez%20de%20la%20Mata%20-%20TFM%20-%20Deep%20Learning%20para%20la%20simulacion%20de%20sistemas%20fisicos.pdf).
