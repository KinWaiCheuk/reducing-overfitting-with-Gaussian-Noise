# solving-overfitting-with-Gaussian-Noise
Preventing overfitting by putting Gaussian noise before the input activation

# Dependencies
Tensorflow 1.5

keras 2.2

sklearn 0.19.1

matplotlib 2.2.2

numpy 1.14.5

# Instruction
All the required codes are contained inside the jupyter-notebook. The code is designed that you can also run it quickly and obtain the results in a PC without a GPU

# Summary

### A Fancy model that overfits
When using a complicated model on a small dataset, the model will overfit easily. As you can see the validation loss (orange curve) for is increasing after training for a long time.
![alt text](https://raw.githubusercontent.com/KinWaiCheuk/solving-overfitting-with-Gaussian-Noise/master/overfits.png)

### The data distribution of MNIST dataset after applying Triplet Neural Newtork
By adding some Gaussian Noise to the input data before the first activation, the overfitting problem can be mitigated
![alt test](https://raw.githubusercontent.com/KinWaiCheuk/solving-overfitting-with-Gaussian-Noise/master/withGaussianNoise.png)
