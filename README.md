## Objectives
The aim of this project is to develop an algorithm that detects faces in images and clusters them into groups of similar faces.

## Approach
1. Face Detection: Utilize the RetinaFace detector for identifying faces in images.
2. Encode the Face Images: Apply various models to encode the detected faces into feature vectors.
3. Clustering: Use the DBSCAN algorithm to cluster the encoded faces.
4. Export Faces: Export faces in each cluster into separate folders for further analysis or usage.

## Face Detector
RetinaFace: Employed for accurate and efficient face detection.

## Models Tested
- VGG-Face
- FaceNet512
- GhostFaceNet
- CLIP

## Clustering
DBSCAN: Density-Based Spatial Clustering of Applications with Noise, used for clustering the encoded face vectors.
