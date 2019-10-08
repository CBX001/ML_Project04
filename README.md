# ML_Project04:
Deep Learning Image Classification - Pneumonia Detection from X-Ray Images using Transfer Learning Inception V3 model.

# Prediction Results:
 - Precision     : 89.74%
 - Recall        : 98.72%
 - F1-Score      : 94.02%

## Transfer Learning:
The use of two transfer learning techniques back-to-back:

1) Freeze the Bottom Layers: to only train the untrained randomly initialised Top Custom layers and usethe weights from the trained Base Model ( 𝐼𝑛𝑐𝑒𝑝𝑡𝑖𝑜𝑛   𝑉3 ).

2) Fine-Tune the Bottom Layers: after training the custom top layers, is to fine-tune the whole model, i.e. train the whole model including the bottom layers using the weighted values.

## Expected outcomes: 
To see a significant improvement in acccuracy and loss between the Frozen adn the Fine-Tune transfer learning steps, with no overfitting.

## Expected benefits: 
- the bottom layers is better generalized for X-Ray images, rather than normal images.
- faster training times, from the reduction in the batch size and number of epochs.
- reduced cost for high-end computing.
- reuse of the final trained model as based-model for X-Ray based Machine Learning Models.

## Background, Credits and References:

- Pneumonia-Detection-from-Chest-X-Ray-Images-with-Deep-Learning _Credit: Anjana Tiha_

- Deep Learning for Detecting Pneumonia from X-ray Images _Credit: Abhinav Sagar_

- Deep Learning Approach to Pneumonia Classification _Credits: Okeke Stephen, Mangal Sain, Uchenna Joseph Maduh & Do-Un Jeong

- CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning _Credits: Pranav Rajpurkar, Jeremy Irvin, Kaylie Zhu, Brandon Yang, Hershel Mehta, Tony Duan, Daisy Ding, Aarti Bagul, Curtis Langlotz, Katie Shpanskaya, Matthew P. Lungren & Andrew Y. Ng_

CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning_Credits: Pranav Rajpurkar, Jeremy Irvin, Kaylie Zhu, Brandon Yang, Hershel Mehta, Tony Duan, Daisy Ding, Aarti Bagul, Curtis Langlotz, Katie Shpanskaya, Matthew P. Lungren, Andrew Y. Ng_

Datasets
Kaggle: Chest X-Ray Images (Pneumonia)
Mendeley: Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification
