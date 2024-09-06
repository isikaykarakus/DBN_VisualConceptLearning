

# Deep Belief Network for Visual Concept Learning



## About
This repository contains the implementation of a Deep Belief Network (DBN) for visual concept learning using the EMNIST dataset, conducted as part of the  Cognition And Computation course at the University of Padua. The project aims to explore computational models of visual concept learning through simulations, with a focus on unsupervised generative models. 

## Project Objectives
The main objectives of the project include:

- **Perform Linear Read-Outs:**
Investigate the disentanglement of sensory representations at different levels of the DBN hierarchy.

- **Analyze Internal Representations:**
Utilize hierarchical clustering and feature visualization methods to analyze the internal representations developed by the model.

- **Visualize Confusion Matrices and Psychometric Curves:**
Create confusion matrices and psychometric curves to understand the model's error patterns, especially under the influence of added noise.

- **Explore Adversarial Attacks and Few-Shot Learning:**
Examine the model's response to adversarial attacks and its capability in few-shot learning scenarios.

## Implementation Details:

### Introduction <br>
The objective is to train and test a Deep Belief Network on the EMNIST dataset to uncover meaningful features. Unlike traditional classifiers, this DBN relies on unsupervised learning, constructing a hierarchy of features without the need for labeled data.

### Model Architecture <br>
The DBN combines generative models with a readout layer. Generative models capture patterns and statistical regularities, while the readout layer extracts valuable information from the generative model's output.

### Training Methodology <br>
The model is trained on the EMNIST dataset, leveraging concepts from class practical sessions and lab materials for Cognition and Computation course.



