Plant BioMetrics Project

Overview
This project focuses on the development of a deep learning model to detect plant leaves and recognize diseases present in them.
The primary goal is to leverage the power of ResNet-50 architecture to identify the plant species and detect diseases on plant
leaves.

Models

Plant Species Identification
I initially created a model using ResNet-50 in a Jupyter notebook (plant_species_identification.ipynb).
This model is designed to identify the species of a plant based on its leaf characteristics.

Disease Detection
Another model was developed using ResNet-50 to detect diseases on plant leaves. 
The Jupyter notebook (disease_detection.ipynb) provides details on training this
model.

Integration
To create a comprehensive solution, I've combined both models in a Python file
(combine_models.py). This integrated model successfully identifies plant species
and detects diseases, achieving an overall accuracy of 89%.
