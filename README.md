# Crack-detection

It's project about crack detection in concrete surfaces.
The dataset with images of various concrete surfaces with and without crack is taken from the website Mendeley Data - Crack Detection, contributed by Çağlar Fırat Özgenel.
The image data are divided into two as negative (without crack) and positive (with crack) in separate folder.

The project consists of several sections:  
- Discover the useful structural information from images with and without cracks using Visualizing the images and Feature detection technique.
- Apply some edge detection technique to extracting features of raw data to support training the algorithms.
- Traine three various Neural Network algorithms on these images:
    1.	MLPClassifier with the GridSearch cross validation method.
    2.	CNN Model
    3.	VGG16-based transfer learning model
- Evaluate performance of the Neural Networks models I trained by use various metrics to determine the best one.
  After comparing the performance of the models, we recommend the VGG16-based model to use as the final model for this analysis.
  The VGG16-based model achieved the highest **Accuracy score** (0.9906) and **F1 score** (0.9907).
