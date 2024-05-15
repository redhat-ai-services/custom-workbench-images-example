# custom-workbench-images-example

This repository is meant to provide some simple examples on how to build custom Workbench Images based on some of the most common use cases. We are also providing the related Tekton pipelines to build and push these images to your image registry.

Here is the repository map:

* ```images```: the directory that contains the example images and their Containerfiles;
  * ```simple-jupyter```: a minimal Workbench based on Jupyter Lab;
  * ```simple-vscode```: a minimal Workbench that uses the VSCode IDE (WIP)
* ```tekton```: all the required objects needed to build and push the images.
  * to install the Tekton components, run ```oc apply -k tekton/```, or ```kustomize build tekton/ | oc apply -f -```.
