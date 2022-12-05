# Face Detection

> It's a algorithm created for project in the Image Processing discipline. 

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
