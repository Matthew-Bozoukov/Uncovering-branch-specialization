# Uncovering-branch-specialization


This is the code for the paper https://arxiv.org/abs/2504.11489 Uncovering Branch specialization in InceptionV1 using k sparse autoencoders. The SAE_FOR_INCEPTIONV1 notebook allows you to create a dataset to train an SAE from activations of Inception V1, train an SAE for inception_V1, visualize the features created, create the branch specialization graphs from the paper, and localize what examples features activate on. The circuits notebook will allow you to create U-Maps of the decoder vectors, and also do circuit analysis. https://huggingface.co/matboz/SAEs_for_inceptionV1/tree/main are where the trained saes are located.


To run these notebooks you dont have to install InceptionV1 as I have the correct version in the notebook. You will need the torch-lucent library to do feature visualization.
