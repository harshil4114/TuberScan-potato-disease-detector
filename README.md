# TuberScan: Potato Leaf Disease Detection using CNNs

TuberScan is a deep learning-based image classification project focused on identifying various diseases in potato plant leaves. Leveraging the power of Convolutional Neural Networks (CNNs), this project aims to automate the process of plant disease detection, which can significantly aid farmers and agricultural professionals in early intervention and crop management.

## 🧠 Technology Stack and Concepts

This project uses TensorFlow and Keras for building and training the neural network model. The primary deep learning concept employed is **Convolutional Neural Networks (CNNs)**. CNNs are particularly well-suited for image data because they are able to extract spatial hierarchies of features through layers of convolutions, activations, and pooling.

The model architecture includes:
- Convolutional layers to detect image features such as edges and textures.
- MaxPooling layers to reduce dimensionality and computation.
- Dense layers for classification after flattening the feature maps.
- Dropout layers for regularization to prevent overfitting.

The model is trained using a batch size of 32 and images resized to 256x256 pixels. It runs for 50 epochs and uses categorical crossentropy as the loss function.

## 📂 Dataset

The dataset used is the "PlantVillage" dataset, which contains categorized images of healthy and diseased potato leaves. However, **due to privacy restrictions and data sharing agreements, the dataset cannot be publicly shared**. If you're interested in replicating or extending this project, you may use the publicly available version of the PlantVillage dataset or gather your own images.

## 📊 Results

The trained model demonstrates promising accuracy in distinguishing between different potato leaf conditions. Future improvements can include data augmentation, transfer learning using pre-trained models like VGG16 or ResNet, and deployment via a mobile or web application.
