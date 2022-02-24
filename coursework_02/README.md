### Image Classification
This image classification problem involved constructing a LeNet5-inspired Neural Network.

This project involved a large dataset of fish images, and the task was to design a neural network for image classification. This neural network was then used in Transfer Learning to finetune parameters for another dataset. In this section, I froze the all except the last layer (and in the next step, the penultimate layer as well), and trained the network on the new dataset. The model performed reasonably well but seems to have been overtrained a bit. In the last section, I discuss various solutions to solve the overtraining issue.

Please check out the .ipynb file to see how I did this!
