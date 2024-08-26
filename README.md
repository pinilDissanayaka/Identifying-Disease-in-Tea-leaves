# Identifying-Disease-in-Tea-leaves

# Tea Leaves Disease Identification

This project focuses on identifying diseases in tea leaves using Convolutional Neural Networks (CNN) with TensorFlow Keras. The dataset used in this project contains images of tea leaves showing 7 common diseases, along with healthy leaves. The goal is to build a model that can accurately classify the type of disease based on the leaf's appearance.

## Dataset

The dataset contains images of tea leaves from Johnstone Boiyon farm in Koiwa location, Bomet county, collected from a clone of 1510. It includes 8 classes:

1. Red leaf spot
2. Algal leaf spot
3. Bird’s eyespot
4. Gray blight
5. White spot
6. Anthracnose
7. Brown blight
8. Healthy leaves

Each class contains more than 100 images. The dataset is suitable for use with transfer learning for machine learning models to predict tea leaf sickness.
[Dataset URL : ](https://www.kaggle.com/datasets/shashwatwork/identifying-disease-in-tea-leafs)

## Model Architecture

The model is based on a Convolutional Neural Network (CNN) architecture built using TensorFlow Keras. It is designed to classify images into the 8 categories mentioned above.

### Key Features:
- **Input Layer**: Accepts images resized to 224x224 pixels.
- **Convolutional Layers**: Multiple layers to capture spatial features.
- **Pooling Layers**: Max pooling to reduce dimensionality.
- **Fully Connected Layers**: To interpret the features extracted by the convolutional layers.
- **Output Layer**: Softmax layer for classification into 8 categories.

## Results

The model achieved an accuracy of **X%** on the test set, indicating its effectiveness in identifying the diseases present in the dataset. The confusion matrix and classification report provide further insights into the performance of the model across different classes.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
