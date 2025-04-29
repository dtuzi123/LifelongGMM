# Lifelong infinite mixture model

>📋 This is the implementation of Training a Dynamic Growing Mixture Model for Lifelong Learning

# Title : Training a Dynamic Growing Mixture Model for Lifelong Learning

# Paper link  


# Abstract

Lifelong learning defines a training paradigm that aims to continuously acquire and capture new concepts from a sequence of tasks without forgetting. Recently, Dynamic Expansion Models (DEM) have been proposed to address catastrophic forgetting under the lifelong learning paradigm. However, the efficiency of dynamic expansion models lacks a thorough explanation based on theoretical analysis. In this paper, we develop a new theoretical framework that interprets the forgetting process of the DEM as increasing the statistical discrepancy distance between the distribution of the probabilistic representation of the new data and the previously learnt knowledge. This analysis provides new insights into model's forgetting behavior. The theoretical analysis shows that adding new components to a mixture model represents a trade-off between model complexity and its performance. Inspired by the theoretical analysis, we introduce a new dynamic expansion model, called the Growing Mixture Model (GMM), where generative data components are added according to the novelty of the incoming task information compared to what is already known. A new component selection mechanism considering the model's already acquired knowledge is employed for updating new DEM's components, promoting efficient future task learning. We also train a compact Student model with samples drawn through the generative mechanisms of the GMM, aiming to accumulate cross-domain representations over time. By employing the Student model we can significantly reduce the number of parameters and make quick inferences during the testing phase.

# Environment

1. Pytorch
2. Python 3.6

# Training and evaluation
>📋 We provide an easy way to train and evaluate the performance of the model.

# BibTex
>📋 If you use our code, please cite our paper as:


