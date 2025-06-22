#  Mini Project: CNN on CIFAR-10

This project demonstrates how to build a Convolutional Neural Network (CNN) from scratch using TensorFlow/Keras to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset contains 60,000 32x32 color images in 10 different classes, with 6,000 images per class.

---

##  Prerequisites

Before diving into this notebook, make sure you're familiar with:

-  Convolutional Layers
-  Pooling Layers
-  Flattening + Dense Layers
-  Data Augmentation
-  Transfer Learning
-  CNN Architectures

---

##  Project Workflow

1. **Load CIFAR-10 Dataset**
2. **Data Preprocessing & Normalization**
3. **Data Augmentation using `ImageDataGenerator`**
4. **CNN Architecture Design**
5. **Training the Model**
6. **Evaluation on Test Set**
7. **Visualization of Performance**

---

##  Libraries Used

- `TensorFlow` / `Keras`
- `NumPy`
- `Matplotlib`

---

##  Results

The CNN was trained and evaluated on the CIFAR-10 dataset. The model achieves a reasonable accuracy using standard convolutional blocks and regularization techniques.

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cnn-cifar10-project.git
   cd cnn-cifar10-project
   
  `
2. Install dependencies:

  ```bash
  
  pip install -r requirements.txt
  ```

3. Run the Jupyter Notebook:

  ```bash
  jupyter notebook
  
  ```

##  Sample Output

Accuracy & Loss Curves

- Test loss: 0.5633
- Test accuracy: 0.8121

Random Predictions with Image Plots
  - Output in notebbok


##  Notes

1. You can improve results further using more advanced architectures like ResNet, VGG, or through transfer learning.

2. Experiment with different augmentations and training epochs.

   

##  Author   :   Priti Kumari 

##  License
This project is open-source and free to use for learning purposes.
