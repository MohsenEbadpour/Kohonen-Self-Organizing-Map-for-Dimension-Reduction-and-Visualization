# Kohonen Self-Organizing Map for Dimension Reduction and Visualization
 
## Overview
The project focused on investigating and implementing a Kohonen Self-Organizing Map (SOM) for dimension reduction and visualization purposes. The dataset used for the project was the "Human Activity Recognition using Smartphones" dataset, which is available at https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones.

First, the dataset was preprocessed, and a fine-tuned Multi-Layer Perceptron (MLP) network was trained on the dataset for classification purposes. Then, a Kohonen SOM was trained on the dataset, and charts related to dead neurons and U-Matrix were reported. The network assumed a 2D neighborhood, and the learning rate was reduced linearly during training.

In the final part of the project, another fine-tuned MLP was trained on the transformed dataset with the mentioned SOM. The results indicated that the dimensionality was reduced from 561 to 81 (an 85% reduction), but the accuracy of classification only reduced from 95% to 87% (a 15% reduction).

The MLPs were implemented using Keras and Python, while the SOM was implemented from scratch in Python and Numpy.

This project was completed as part of the "Neural Networks" (changed to "Neural Computing and Deep Learning") course at Amirkabir University of Technology (AUT) in Tehran, Iran, taught by Professor Reza Safabakhsh(<safa@aut.ac.ir>). I took this course during my Master of Science degree in Computer Engineering at AUT in Spring 2022.

**A Sample that indicates records from the same class are mapped similarly**
![Output](/output.png)


## Contributions

Contributions to the project are welcome. If you find a bug or want to suggest an improvement, please open an issue or submit a pull request.

## License

This project is licensed under the GPL-3.0 License. Please see the LICENSE file for more information.

## Contact

If you have any questions or want to get in touch with me, you can send an email to <m.ebadpour@aut.ac.ir> or open a conversation via pull request on GitHub. I hope this project can be helpful to others who are interested in learning more about neural networks and deep learning.
