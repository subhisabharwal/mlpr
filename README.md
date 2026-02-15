# MLPR
Machine Learning Lab 5 project implementing face detection, HSV feature extraction, K Means clustering, and template image classification using distance based learning and visualization techniques.
# Aim
The aim of this lab is to perform distance based classification and clustering using facial image data. The experiment focuses on extracting Hue and Saturation features from detected faces, applying K Means clustering, and classifying a template image based on cluster proximity.
# Methodology
## 1.face detection
    Haar Cascade Classifier is used to detect faces in the input image.
    Detected faces are enclosed using bounding boxes.
## 2.feature extraction
    The image is converted from BGR to HSV color space.
    For each detected face, the mean Hue and Saturation values are extracted.
## 3.clustering
    K Means clustering (K = 2) is applied on Hue Saturation features.
    Faces are grouped into clusters based on color characteristics.
## 4.visualization
    Hue Saturation scatter plots are generated.
    Cluster centroids are plotted.
    Detected faces are visualized as markers in feature space.
## 5.template classificaton
     A template image is converted to HSV.
    Its Hue Saturation features are extracted.
    The trained K Means model predicts the cluster label of the template image.
# Key findings
    Faces with similar color characteristics are grouped into the same cluster.
    Hue Saturation space provides better separation than RGB space.
    The template image is successfully classified into one of the learned clusters.
    K Means clustering effectively performs unsupervised classification.
# Conclusion
This lab demonstrates how distance based machine learning techniques can be applied to real world image data. By working in HSV space and using K Means clustering, meaningful groupings of facial images are obtained. The experiment highlights the importance of feature selection and distance metrics in pattern recognition tasks.Real world application of this extends to Face Recognition,Medical diagnosis and Handwritten digitak recognition etc.
  
