
Physics informed data-driven near-wall modelling for lattice Boltzmann simulation
===============

PINN  provides a data driven model to solve wall models in turbulence modelling with LB method. The trainig process is realized by pytorch.


Raw data
------------
The traing and test dataset are obbtained from a high precision simulation. Data of two samplings ('sparse' and 'dense') are provided in the path './data' .

The file 'y2d' is the position of the grid in normal-to-wall direction. The files 'u' and 'yp-instant' are the velocities and position of the samples.



Training
------------
Two training methods are provided in the folder './training'. The script 'NNWC' is the training method process without PDF correction, and the script 'NNPC'

is the training process with PDF correction.


Model implementation and visualization
----------
The model is visualized by prediction. The prediction is realized by script 'plots' in './visualization'


Cite this work
----------
```
@article{xue2024physics,
  title={Physics informed data-driven near-wall modelling for lattice Boltzmann simulation of high Reynolds number turbulent flows},
  author={Xue, Xiao and Wang, Shuo and Yao, Hua-Dong and Davidson, Lars and Coveney, Peter V},
  journal={arXiv preprint arXiv:2402.08037},
  year={2024}
}
```
