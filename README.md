Name: Md Sourav Hossain
ID:210141
# cnn-phone-classification
# CNN-Based Image Classification with Real-World Testing

## Dataset
- Standard Dataset: FashionMNIST (Torchvision)
- Custom Dataset: 10 smartphone images (Shirt, Sneaker, Bag, Trouser)

## Model Architecture
- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Fully Connected Layers
- Loss: CrossEntropyLoss
- Optimizer: Adam

## Training
- Batch Size: 64
- Epochs: 5
- Input Size: 28×28 (Grayscale)

## Evaluation
- Training & Validation Loss/Accuracy plots
- Confusion Matrix on test set
- Visual Error Analysis

## Real-World Testing
The trained CNN model was tested on real smartphone images.
Each image was resized, normalized, and classified using the same
preprocessing pipeline as the training data.

## Files
- `dataset/` → Custom phone images
- `model/210141.pth` → Saved trained model
- `210141.ipynb` → Google Colab Notebook

## Links
- GitHub Repository: <(https://github.com/sourav277/cnn-phone-classification)>
- Google Colab: <(https://colab.research.google.com/drive/10DUYYIOjPkYACaWItbzzY-nfvfq2lwzE#scrollTo=8QlUz7agdiiv)>

