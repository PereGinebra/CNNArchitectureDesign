Project for my Bachelor's Thesis in Computer Science.
</br>
</br>

---


# Designing Convolutional Neural Networks for Classification of Metastatic Tissue in the Lymph Nodes
## Evaluation of the Effect of Feature Map Distributions Across Convolutional Layers on Network Performance
</br>
This project was developed to answer to some extent the question: how does an Artificial Neural Network's (ANN) architecture design affect its performance? 
A more specific question that it gets closer to answering could be: how does the distribution of feature maps across convolutional layers affect the [metastatic tissue] image classification performance of a Convolutional Neural Network (CNN)?
</br>
</br>
For a more detailed explanation of the project and its outcomes, refer to abstarct or the full report added in the repository. 
</br>
</br>

---
## Jupyter Notebooks
The 3 jupyter notebooks used each have their own task:
- [DefineArchitectures](./DefineArchitectures.ipynb) is the notebook used to define and store new architectures quickly in the form of untrained models.
- [ModelTrainingAndTesting](./ModelTrainingAndTesting.ipynb) is the notebook used to train and test archtiectures and models as well as store the results of these procedures.
- [GenerateGraphs](./GraphGeneration.ipynb) is the notebook used to generate graphs with the data obtained from the previous notebook.

</br>

---
## File hierarchy
The code in this project is very dependent on the file hierarchy used to store different data. Here you can see it briefly defined:
- ./datasets/Cancer Detection/labeled images/ : PCam Dataset location. Divided into 2 folders (named '0' and '1') according to their label. 
- ./Graphs/ : Location where graphs generated in the *Graph Generation* notebook are stored.
- ./Models/ : Location where the untrained models/architectures defined in the *Prepare models for testing* notebook are stored. Each model is stored in one of the 5 sub-directories (/up, /down, /hill, /valley, /flat) according to their design. 
- ./Results/ : Location where all the results are stored. The training histories are stored in a csv file inside the subdirectory "/history CSVs". Test results of trained models are stored in the subdirectory "/Test Results". The txt files containing the history+final result of each model are stored in one of the 5 subdirectories (/up, /down, /hill, /valley, /flat) according to the model design.
- ./Trained Models/ : Location where the fully trained models are stored.
