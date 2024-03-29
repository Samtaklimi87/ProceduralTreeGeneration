# ProceduralTreeGeneration 
In our research aimed at efficiently predicting tree branches from their foliage, we utilized the Pix2Pix algorithm. We adapted its code to align with our objective, which focuses on using a Generative Adversarial Network (GAN) to separate leaves from branches.

Here is the link to the original Colab notebook for Pix2Pix: Pix2Pix Colab Notebook(https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/generative/pix2pix.ipynb#scrollTo=_xnMOsbqHz61&uniqifier=1). 

As mentioned in the report, this notebook serves as a reference for the Pix2Pix implementation. 

# Combine_A_and_B'
To combine Folder A and Folder B, use the script 'combine_A_and_B.' Make sure to modify the path to your data.

# Our Data 
To use our dataset, you have two options:

1. Edit the Path/Directory Code: You can modify the path/directory in our source code by changing the path to match the location of your dataset on your machine.

2. Download and Use it Locally: Alternatively, you can download the dataset and use it in the path on your machine.

# Jupyter Notebook
Our Python code is available in a Jupyter Notebook, where you can find detailed information on building the generator and discriminator of our neural network.

# Training of the model 
Pix2Pix itself suggests using at least 40,000 steps for training. However, due to time constraints and GPU limitations, our experiments were conducted with 20,000 steps. Despite this, we achieved promising results. If you have the resources, feel free to train the model for more than 40,000 steps for potentially improved performance.
