# DeepLearning-Satellite-Imagery-Data-Preparation
Welcome to the Satellite Imagery Deep Learning Dataset Creation repository! This repository provides a comprehensive guide and tools to help you create custom deep learning datasets using your own satellite imagery, a crucial yet often overlooked step in geospatial deep learning workflows.

Motivation :

Most satellite remote sensing based deep learning tutorials and frameworks rely heavily on preloaded, benchmark datasets like ImageNet, EuroSAT for image classification, segmentation, and other computer vision tasks. However, in many real-world applications, you need to work with your own custom imagery, which often requires a different approach for data preprocessing, annotation, and dataset structuring.

This repository bridges that gap by showing you how to:

Load and preprocess your satellite imagery from various formats (GeoTIFF, HDF5, etc.)
Annotate and label your images for different machine-learning tasks
Augment your data to improve model generalization
Prepare datasets for deep learning frameworks like PyTorch, TensorFlow, or Keras
By the end of this guide, you can generate a high-quality, custom dataset from your satellite images and apply it to your deep-learning models.

![image](https://github.com/user-attachments/assets/c4c703a7-b56f-48c8-a2f7-08f92084d557)

![image](https://github.com/user-attachments/assets/0f671633-c51d-43a1-8289-3772f23ec252)


Features
Step-by-step instructions to import and preprocess satellite imagery from your own sources.
Tools to label and annotate images for tasks like classification, object detection, and semantic segmentation.
Data augmentation techniques specifically designed for satellite imagery (rotation, flipping, scaling, and more).
A custom dataset loader for deep learning libraries (PyTorch, TensorFlow).
Code to convert geospatial datasets into formats usable for training models (e.g., .npy, .tfrecord).


Background :

The satellite imagery used in this project is Sentinel-2 imagery of a Himalayan landscape. This terrain features an intricate network of drainage systems, whose accurate monitoring is crucial for understanding the region's geomorphological changes. The data preparation steps involves extracting the water bodies from the NDWI image and converting it to a shapefile in a GIS environmnent and merging the NDWI image with the preexisting bands of the satellite image. 
