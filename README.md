<img width="1274" height="765" alt="image" src="https://github.com/user-attachments/assets/783cd8b4-c2bd-4d6e-8e07-b5e41f37e4de" />
<img width="597" height="313" alt="image" src="https://github.com/user-attachments/assets/18d2e887-b942-4424-ba6f-216355622b1f" />
<img width="1474" height="584" alt="image" src="https://github.com/user-attachments/assets/7adf78f5-aa89-45e9-bfc1-cf2bd3c465f7" />
<img width="758" height="666" alt="image" src="https://github.com/user-attachments/assets/3f3091bd-4927-4543-93d8-7c722777387b" />
<img width="1138" height="397" alt="image" src="https://github.com/user-attachments/assets/275cbbef-87bd-41db-8a11-dd2e959856dc" />

Short decscription.....

This project implements a Convolutional Neural Network (CNN) to classify geometric shapes (circle, square, triangle) using both a standard training dataset and real images captured on a phone. The workflow consists of three main stages:

Training – Images are preprocessed with resizing, tensor conversion, and normalization before being fed to the CNN. The model uses three convolutional layers with ReLU activations and max-pooling to extract hierarchical features, followed by fully connected layers for classification. The network is trained over multiple epochs using cross-entropy loss and the Adam optimizer, while tracking the loss and accuracy per epoch. Training progress is visualized with line plots showing how the model’s loss decreases and accuracy improves over time.

Evaluation on Phone Images – After training, the model is evaluated on real images from the phone dataset. Each image is transformed and passed through the trained CNN, and predictions are compared with true labels. A grid of images is displayed, showing both the true class and predicted class along with prediction confidence, providing an intuitive view of model performance on real-world data.

Visualization – The architecture includes robust visualization steps: plotting training loss and accuracy trends to monitor learning, and displaying predictions on individual images to inspect classification quality. This combination of CNN feature extraction, fully connected classification, and clear visual feedback demonstrates a complete end-to-end pipeline for image classification tasks.



