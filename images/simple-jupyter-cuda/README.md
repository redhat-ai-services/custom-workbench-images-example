## Simple Jupyter Workbench image

In this directory, you can find the required files to build a minimal Jupyter Lab Workbench image with the addition of CUDA.

The base container image is a Red Hat UBI9 image which ships with Python 3.11 already installed. <br>
If you want to make any changes to the installed Python packages, edit the ```requirements.txt``` file with the desired changes. <br>
In the ```Containerfile```, you can find some useful resources about the installation of CUDA, reported here for ease of reference: <br>
* [Officially maintained CUDA Image](https://gitlab.com/nvidia/container-images/cuda/-/blob/master/dist/12.4.1/ubi9/base/Dockerfile)
