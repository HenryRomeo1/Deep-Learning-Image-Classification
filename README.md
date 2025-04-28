## 🐱🐶 Deep Learning: Image Classification (Cats vs Dogs)

**Problem Statement**:  
Classify images as cat or dog using a deep learning convolutional neural network.

**Data**:  
- Source: TensorFlow Datasets [`cats_vs_dogs`](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs)
- Description: 25,000 labeled images of cats and dogs.

**Data Mining Operations**:  
- Data wrangling: Resized and normalized image data.
- Modeling: Used MobileNetV2 pre-trained CNN for transfer learning.
- Libraries: `tensorflow`, `keras`, `numpy`
- Reason for model choice: MobileNetV2 provides high accuracy with efficient computational resources.

**Model Outputs**:  
- Achieved 98% validation accuracy.
- Plotted training and validation loss/accuracy curves.

**Limitations**:  
- Highly curated dataset may not generalize perfectly to wild images.
- Limited augmentation might underprepare model for unseen conditions.

**Were you able to effectively solve the problem?**  
Yes, the model achieved very high accuracy on test data, successfully solving the classification task.
