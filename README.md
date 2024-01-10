# Face Detection

> It's a algorithm created for project in the Image Processing discipline at Universidade Federal de Ouro Preto. 

It uses a pre-existing dataset with faces of presidents, and in this dataset, some photos of Mark Zuckerberg were manually added. During the training and prediction of the model, images are pre-processed to ensure higher accuracy. The algorithm analyzes each frame of a video, using a detector to segment the faces and the trained model to identify the face.

### Resources
- Python Notebook
- OpenCV
- Sklearn
- Matplotlib
- EUA presidents database
- Custom Zuckerberg database

### Implemetation
1. Load a Presidents Database and include Mark Zuckerberg samples 
2. Preprocess Samples (Crop, Resize and Convert to gray scale) 
  - Use model to detect face and crop (**Face Detector**)
  - Resize to standardize samples
4. Apply label encoder
5. Train LBPH+SVM model to recognize person by processed samples
6. Apply preprocess operators and recognize model on video getting prediction by frame
7. Save video with predictions drawned on each frame
