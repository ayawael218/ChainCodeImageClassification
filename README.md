# ChainCodeImageClassification
1) Description:
    The project applies chain code feature extraction on 3x3 blocks of binarized MNIST images and uses a RandomForest classifier for digit classification.

3) Key Features:
  Feature Extraction: Binarized images split into 3x3 sub-images, extracted contours, and computed chain codes (padded or truncated to 100).
  RandomForest Classifier: Trained with 100 estimators and 30% of the data for testing.
  Performance:
  Test Accuracy: 86%

3) Programming Tools:
    Python, OpenCV, NumPy, Scikit-learn, TensorFlow
