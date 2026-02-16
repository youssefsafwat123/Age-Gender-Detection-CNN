# Age-Gender-Detection-CNN
Project to detect person age and gender from images (NTI Deep learning Course)

# Age and Gender Prediction using CNN
A multi-task deep learning model built with TensorFlow/Keras and trained on Kaggle.

## Performance
- **Age Prediction:** ~5.09 MAE (Mean Absolute Error)
- **Gender Classification:** ~82.5% Accuracy
- **Training Time:** 52 minutes on Tesla T4 GPU

## Dataset
Trained on the **UTKFace** dataset containing 20k+ face images.

## Setup
1. Clone the repo.
2. Install dependencies: `pip install tensorflow pandas matplotlib`.
3. Run the notebook to see results.

## 🚀 How to use
The model weights (~290MB) exceed GitHub's upload limit. 

1. **Download Weights:** You can find the trained `.keras` file in the **Output** section of my Kaggle notebook here: [https://www.kaggle.com/code/youssefsafwat1/deep-learning-classification-and-regression]
2. **Run Inference:** Load the model using:
   ```python
   from tensorflow.keras.models import load_model
   model = load_model('your_model_filename.keras')
