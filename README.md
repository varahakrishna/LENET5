# LENET5
# LeNet5-Impemenation
Results on the MNIST dataset:
Accuracy of the network on the 10000 test images: 98.93 %
![image](https://github.com/varahakrishna/LeNet5-Impemenation/assets/114026298/702c4fb0-187b-4af8-ba95-6c46b60099d5)
The above code evaluates the trained model on the test set of the MNIST dataset and prints out the confusion matrix and classification report.
![image](https://github.com/varahakrishna/LeNet5-Impemenation/assets/114026298/4613e94d-9bf8-41ed-8441-35fcb779b4e1)
This shows how the model's predictions on the test set were plotted on the confusion matrix. For each image in the test set, the true and predicted labels are first extracted. The confusion matrix function from sci-kit-learn is then used to construct a confusion matrix from these labels. Using Matplotlib, the confusion matrix is then shown, with each cell indicating the number of times the model correctly identified a picture with a true label corresponding to the row and a predicted label belonging to the column. Correct classifications are represented by the confusion matrix's diagonal members, whereas wrong classifications are represented by the matrix's off-diagonal elements. Each cell's hue and value show how frequently the matching true/predicted label pair occurs. Additionally, the code has some formatting and labeling to make the plot more readable.

![image](https://github.com/varahakrishna/LeNet5-Impemenation/assets/114026298/4ec3dd30-1885-4233-b9b5-e901f0146887)
By iterating over each epoch and gathering the loss, the algorithm trains a neural network
model using the MNIST dataset. The list "train losses" contains the training loss for each epoch. Once all epochs have been completed, the script uses the matplotlib library to plot a graph showing the loss against the number of epochs. By examining the loss's declining trend, the
graph provides an understanding of how well the model is doing during training.
Analysis of your results on the MNIST dataset:
![image](https://github.com/varahakrishna/LeNet5-Impemenation/assets/114026298/126bdca9-5fbf-492c-bfc7-14ab74f64440)
![image](https://github.com/varahakrishna/LeNet5-Impemenation/assets/114026298/949bd1c8-9741-4854-a30a-e082c0b8d0eb)
The above image is the sample image from the data set of MNIST.


References:
 Explaining precision and recall. The first days and weeks of getting… | by Andreas Klintberg | Medium
 https://blog.paperspace.com/writing-lenet5-from-scratch-in-python/
 https://towardsdatascience.com/implementing-yann-lecuns-lenet-5-in-pytorch-5e05a0911320

The above image is the sample image from the data set of MNIST.


References:
 Explaining precision and recall. The first days and weeks of getting… | by Andreas Klintberg | Medium
 https://blog.paperspace.com/writing-lenet5-from-scratch-in-python/
 https://towardsdatascience.com/implementing-yann-lecuns-lenet-5-in-pytorch-5e05a0911320
