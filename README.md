# pdf-summarizer

<img width="1032" height="628" alt="Screenshot 2026-11-01 104631" src="https://github.com/user-attachments/assets/98b459f8-5de3-4f77-b30b-931082c7d281" />
**Summary:**

To address the limitations of RT-PCR testing and the challenges of manually diagnosing COVID-19 from radiography, researchers developed **DLH_COVID**, a custom convolutional neural network (CNN) designed to classify chest X-ray images into three categories: COVID-19, pneumonia, and normal/healthy. 

**Key Highlights:**
* **Model & Methodology:** The custom architecture—consisting of three convolutional layers and two fully connected layers—was trained on a dataset of 6,432 chest X-ray images. It was optimized using Stochastic Gradient Descent (SGD) and dynamic learning rate scheduling, then benchmarked against several pre-trained models (including ResNet, VGG, Inception, and EfficientNet).
* **Performance:** DLH_COVID outperformed the transfer learning models, achieving roughly 96% accuracy on the validation set and a 95% average accuracy across 5-fold cross-validation. 
* **Deployment:** The model was integrated into a public, cloud-based web application that provides real-time diagnostic predictions and probability scores within seconds to aid clinical workflows.
* **Limitations:** The authors noted that performance was somewhat constrained by image resolution issues and class imbalance (fewer COVID-19 samples), suggesting that larger datasets and clinical trials will be needed to further improve diagnostic reliability.
