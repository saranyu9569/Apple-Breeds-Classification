
# Apple Breeds Classification

This project aims to classify apple breeds from images using machine learning and deep learning models.  
The models include Convolutional Neural Networks (CNN), Random Forest (RF), Decision Tree (DT), and a hybrid approach combining Color Histogram Feature Extraction with CNN.

## Models Used

1. **Feature Extraction + CNN:** Combined color histograms (from HSV color-space) with CNN features.
2. **Convolutional Neural Networks (CNN):** Trained on raw image data to learn patterns specific to apple breeds.
3. **Random Forest (RF):** Trained on flattened image data as input features.
4. **Decision Tree (DT):** Used for comparison with simpler tree-based models.

## Results

| Model                     | Validation Accuracy |
|---------------------------|---------------------|
| Feature Extraction + CNN  | 1.00 |
| Convolutional Neural Network (CNN) | 96.0 |
| Random Forest (RF)        | 0.87 |
| Decision Tree (DT)        | 0.65 |


## Requirements

This project requires Python 3.8 or higher and the following libraries:
- TensorFlow
- Scikit-learn
- OpenCV
- NumPy
- Matplotlib

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Usage

1. Load the dataset in `./dataset` directory, ensuring images are organized by folders representing class labels.
2. Run the notebook `apple_breeds_updated.ipynb` to train models and evaluate performance.
3. Results will be displayed in the notebook, and accuracy metrics will be updated in this README.

