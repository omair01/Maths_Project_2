Project Definition

The goal is to classify input images into one of two categories. The CNN model and the Vision Transformer (ViT) model will be trained and evaluated on the same dataset to compare their performance in terms of accuracy and loss.

Why CNN vs ViT

In computer vision tasks, Convolutional Neural Networks (CNNs) have been the dominant architecture for image classification and object detection tasks. However, recently, Vision Transformer (ViT) has emerged as a new architecture for computer vision tasks that is based on the Transformer architecture used in Natural Language Processing (NLP) tasks.

The idea behind ViT is to replace the convolutional layers in a CNN with a self-attention mechanism that allows the model to capture global dependencies between the image pixels, instead of just local ones. This has shown promising results in image classification tasks and has been shown to outperform CNNs on some benchmarks.

In this project, we aim to compare the performance of a CNN and a ViT model on a specific image classification task. By doing so, we hope to gain insights into the strengths and weaknesses of each architecture and identify which one is better suited for this particular task.

To achieve this, we first implemented a CNN model using the Keras library and trained it on a dataset. We then implemented a ViT model using the Transformers library and trained it on the same dataset. We compared the performance of these two models in terms of accuracy and training time. From the results, we can determine which model performed better and draw conclusions about the suitability of each model for this task.





