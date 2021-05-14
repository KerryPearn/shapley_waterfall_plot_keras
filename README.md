# Waterfall plot for visualising Shapley values

This notebook contains a function for creating a waterfall plot using the shapley values as calculated using the SHAP library. The motivation behind this was that currently the SHAP library offers this functionality for some models, for example logistic regression, however not for all models, for example keras models that use DeepExplainer.

Environment yml files are provided in the binder folder. Use environment.yml when no GPU is available, and environment_gpu.yml when a GPU is available. Instructions are given in the Binder folder.
