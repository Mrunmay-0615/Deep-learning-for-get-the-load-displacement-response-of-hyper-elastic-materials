# Deep-learning-for-get-the-load-displacement-response-of-hyper-elastic-materials

The repository contains jupyter notebooks corresponding the neural network solutions of the deformation of hyperelastic materials subjected to certain loading conditions:

* AxialBar1D_Linearly_Elastic.ipynb: A linearly-elastic axial-bar
* 2DBeamv5 (3).ipynb: Cantilever Beam
* AxialBar_StrongForm.ipynb: Solution using the strong form
* Axial_Bar_Weak_Form (1).ipynb: Solution using the weak form
* FSB_Pytorch (1).ipynb: A Beam fixed at both the ends

For every notebook, the initial cell defines the integration class and the nn Model class, followed by the implementation of specific geometry DEM class that will solve the problem
I have also plotted the heat maps of the solutions obtained for the important displacement values as well as the VonMises Stress.

 Here is an example of the same for the cantilever beam bending:

 ![image](https://github.com/Mrunmay-0615/Deep-learning-for-get-the-load-displacement-response-of-hyper-elastic-materials/assets/105450337/b8d5c2a7-15c6-4e1f-a4e8-99c925978d32)
 ![image](https://github.com/Mrunmay-0615/Deep-learning-for-get-the-load-displacement-response-of-hyper-elastic-materials/assets/105450337/90341bde-491b-4c0b-84e6-057069fae524)

