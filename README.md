# Neural Operators for Bypassing Gain and Control Computations in PDE Backstepping

The source code for the paper titled Neural Operators for Bypassing Gain and Control Computations in PDE Backstepping (TODO: add arxiv link).

## Sysetm Requirements
All of the code is written in Python 3 and relies on standard packages such as numpy, Pytorch, Scipy, and the 
deep learning package [DeepXDE](https://github.com/lululxvi/deepxde). Additionally, all code
in this work is nicely formatted in a jupyter-notebook. A basic installation
will require the installation of Python, jupyter along with DeepXDE and PyTorch. Please see the 
import statements in the Jupyter-notebooks to make sure all files are included. 

## Demos

### Dataset and Models
All precomputed datasets and models are available here [Google Drive](https://drive.google.com/drive/folders/151SIUPUdzbTIkRxjSfIt1YEv88AYkzhx?usp=sharing)

### Learning mapping $$\beta$$ to $$k$
- Please see the jupyter-notebook in the folder titled **betaToK**
- This model will only take a few minutes to generate the dataset and train. However, we still provide the data and model in the Drive folder above. To generate your
own datasets, please uncomment the labeled code in the notebook.

### Learning mapping $$\beta$$, $$u$$ to $$U$
- Please see the jupyter-notebook in the folder titled **betauToU**
- This model will take only around 10 minutes for the dataset generation and around 20 minutes to train. Feel free to use the data and model given in the Drive folder above. 
Otherwise uncomment the code labeled in the notebook

### Learning mapping $$f(x, y)$$ to $$k(x, y)$
- Please see the jupyter-notebook in the folder titled **fToK**
- This model will take around 15 minutes for the dataset generation and around 5 minutes to train. Feel free to use the data and model given in the Drive folder above. 
Otherwise uncomment the code labeled in the notebook. To generate high-resolution figures as in the paper, it will take around a half-hour to solve the kernel and PDE. 
Please see the comments inside the notebook. 

## Cite this work
TODO

## Questions
Feel free to leave any questions in the issues of Github or email the author Luke at lbhan@ucsd.edu

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
