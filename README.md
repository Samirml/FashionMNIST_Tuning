# Fashion MNIST Training with PyTorch


## Description
This repository contains a PyTorch implementation for training and validation a neural network on the Fashion MNIST dataset. The training process includes various configurations, such as different learning rates, total iterations, and scheduler types. We will solve the problem of classifying Fashion MNIST images using fully connected neural networks using advanced model training stabilization techniques - Batch Normalization, LR scheduler. Also, we will use wandb service for logging versions.

Here is the visualization of schedulers (Exponential Decay is using here):
![image](https://github.com/user-attachments/assets/7af8db89-471a-43b0-a1c1-64fc3882059c)


## Technologies used
- **Python 3.8+**
- **PyTorch**
- **torchvision**
- **NumPy**
- **tqdm** 
- **wandb** 

  
## Scheme of the program operation

The program consists of a single file that provides training of the implemented model and testing it on a deferred sample.

The program was tested on GPU T4 x2 on kaggle platform. 
To speed up performance, we recommend running on a graphics card with a GPU.

In order to launch a project, you need to:

1. Clone repository
```bash
git clone https://github.com/yourusername/fashion-mnist-training.git
cd fashion-mnist-training
```
2. Install the required packages:
Linux:
```bash
pip install torch torchvision numpy tqdm wandb
```
3. Set up Weights and Biases (WandB) using your secret token:
Linux:
```bash
wandb login
```
4. Run the training script:
Linux:
```bash
python fashionmnist-tuning.py
```

You will see logging with wandb and experiments
![image](https://github.com/user-attachments/assets/8ff1063f-a147-46e6-97b9-25368c846c74)



## License
The oicture of schedulers was taken from Karpov.Courses (https://karpov.courses/deep-learning?_gl=1*gvc6ll*_ga*NDI1MzY4NTU3LjE3MjM5NzU4OTE.*_ga_DZP7KEXCQQ*MTcyNTg3MzAyNi4xMTYuMC4xNzI1ODczMDI2LjYwLjAuMA..).

## Authors and contacts
To contact the author, write to the following email: samiralzgulfx@gmail.com



