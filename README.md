#   Wildfire Image Classification Project

## Team Members
- Ghaith Chrit (Ghaith-Chrit)
- James Partsafas (JamesPartsafas)
- Kenny Phan (kennyphan100)
- Guillermo Tremols (KubrayKan)

## Project Summary

### Project Definition

The project aims to develop a robust model for classifying wildfire images from various angles. The primary objective is to empirically evaluate and compare the performance of different models in classifying images as containing fire or not. Two main classes of models will be employed: supervised models including Convolutional Neural Networks (CNN) and Vision Transformer (ViT), and an unsupervised model using K-means clustering (more models maybe added if needed). Human labels will be incorporated at the final stage of the unsupervised model.

### Model Design

-   **Supervised Models:**
    
    -   **CNN:** Utilized for image classification, CNNs are known for their effectiveness in capturing spatial hierarchies. The model will be trained on labeled wildfire images.
    -   **ViT:** Employing transformer architecture, ViT will be utilized to explore the attention mechanism's performance in image classification.
-   **Unsupervised Model:**
    
    -   **K-means Clustering:** Applied as an unsupervised approach to categorize images without human labels. Human labels will be assigned based on the clusters identified by the K-means algorithm.

### Dataset Description

The dataset comprises wildfire images captured from various perspectives to enhance result versatility. The following is the list of datasets that will be used (more datasets maybe added):

 - [Satellite Images](https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset)
 - [(Mostly) Front Facing Images](https://www.kaggle.com/datasets/ahmedsaleemmahdi/wildfire)
 - [Aerial Images](https://www.kaggle.com/datasets/anamibnjafar0/flamevision)

### Research Questions

1.  Which model (CNN, ViT, or K-means clustering) performs best in classifying wildfire images?
2.  What features do the supervised models (CNN and ViT) focus on for classification?

### Algorithms and Techniques

-   **Supervised Models:**
    
    -   CNN and ViT for image classification.
    -   Feature visualization for interpreting model focus.
    -   Heatmap generation to identify regions of interest.
-   **Unsupervised Model:**
    
    -   K-means clustering for unsupervised categorization.
    -   Incorporation of human labels based on clustered results.

### Data Preprocessing

-   Data Augmentation: Image Resizing and Random (Horizontal) Flip 
-   Removal of corrupted images.
-   Detection and handling of near-duplicate images.
-   Integration of human labels in the unsupervised model's final stage.

The project seeks to provide insights into effective wildfire image classification models, leveraging both supervised and unsupervised learning approaches. Results will be validated through comprehensive evaluations and visualizations, ensuring a holistic understanding of model performance and limitations.