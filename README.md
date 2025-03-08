# Pruning_Network
- Use Iterative Pruning to reduce model size and maintain accuracy. 
- The first ipynb file , contains the basic code for Network Pruning . 
- The second file shows a pruned model . The model taken for traininf was the MNIST dataset . This dataset contains many images of handwritten digits . There are a total of 70000 such images . The training dataset has 60000 images and testing dataset has 10000 images . This means that the training is done on 6/7th of the whole dataset , ie ~ 85.3% of the dataset is used in training and the remaining 14.7% is used for testing . 
- During the pruning , 30% of the weights and biases of both the convolutional layers initialised were pruned . The learning rate was set to 0.01 .
  
## Summary :

### Before Pruning:

- Time taken = 4 min 32 seconds 
- Average Accuracy of Testing over 5 epochs = 96.494% 
- Performance on Random Image = 100% as expected
  
### After Pruning :

- Time taken = 4 min 30 seconds
- Average Accuracy of Testing over 5 epochs = 96.69%
- Performance on Random Image = 100% as expected 

