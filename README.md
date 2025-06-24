# Transfer-Learning-for-Image-Classification-using-MobileNetV2-and-ResNet50
This project applies transfer learning using pre-trained MobileNetV2 and ResNet50 models to perform image classification on a custom dataset. Both models were evaluated using feature extraction and full fine-tuning approaches.

Preprocessing:
Images resized to 224×224, normalized using ImageNet mean and std. Loaded with PyTorch’s ImageFolder and DataLoader.

Models Used:

MobileNetV2 (full fine-tuning of top layers)

ResNet50 (standard fine-tuning)

Training:
Used Adam optimizer, learning rate scheduling, and dropout for regularization. Models trained for N epochs with mini-batches.

Evaluation:
Evaluated on the validation set using:

Accuracy: XX% (MobileNetV2), YY% (ResNet50)

F1-Score: AA (MobileNetV2), BB (ResNet50)

MobileNetV2 was observed to perform better in terms of training efficiency and achieved comparable or better generalization than ResNet50 on this dataset.


Dataset : https://www.kaggle.com/datasets/andrewmvd/face-mask-detection
