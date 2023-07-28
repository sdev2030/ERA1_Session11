# ERA1_Session11
## Assignment
       Your assignment is to build training structure and train ResNet18 on Cifar10 for 20 Epochs. The assignment must: 
        1. pull your Github code to google colab (don't copy-paste code) 
        2. prove that you are following the above structure 
        3. that the code in your google collab notebook is NOTHING.. barely anything. There should not be any function or class that you can define in your Google Colab Notebook. Everything must be imported from all of your other files 
        4. your colab file must: 
            1. train resnet18 for 20 epochs on the CIFAR10 dataset 
            2. show loss curves for test and train datasets 
            3. show a gallery of 10 misclassified images 
            4. show gradcam output on 10 misclassified images.

## Solution - Notebook [s11_assignment](https://github.com/sdev2030/ERA1_Session11/blob/main/s11_assignment.ipynb)
In this we will use RESNET18 architecture to achieve target test accuracy of more than 90% from the 19th epoch.

Following are the model parameter, train and test accuracies achieved in training the model for 24 epochs.
- Model Parameters - 11,173,062
- Train Accuracy - 92.48%
- Test Accuracy - 90.98%

Graph showing LR finder to determine the optimum learning rate to use in one cycle LR policy.
![LR finder Graph](https://github.com/sdev2030/ERA1_Session11/blob/main/images/lr_finder_graph.png)

Graphs from training showing loss and accuracy for train and test datasets
![Training Graphs](https://github.com/sdev2030/ERA1_Session11/blob/main/images/training_graphs.png)

Ten misclassified images from the trained model.
![Misclassied images](https://github.com/sdev2030/ERA1_Session11/blob/main/images/wrong_classified.png)

Gradcam on Ten misclassified images from the trained model.
![Misclassied images](https://github.com/sdev2030/ERA1_Session11/blob/main/images/gradcam_wrong_classified.png)
