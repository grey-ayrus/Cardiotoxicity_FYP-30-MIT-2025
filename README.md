# Cardiotoxicity_FYP-30-MIT-2025

## LSTM-based Heart Sound Classification

This project implements an LSTM-based model for classifying heart sounds using MFCC and additional spectral features. The model is trained on audio data and aims to improve classification accuracy using advanced preprocessing and augmentation techniques.

## Features
- Transformer-based model for heart sound classification.
- Uses MFCC, Mel Spectrogram, and Chroma features.
- Supports data augmentation techniques like noise addition and pitch shifting.
- Evaluation metrics include Confusion Matrix, ROC Curve, and F1 Score.

## Installation
```bash
pip install torch torchaudio scikit-learn matplotlib
```

## Dataset Preparation
Ensure you have a dataset of heart sounds stored in `.wav` format. Organize the data into `train`, `val`, and `test` directories.

## Usage

### Training the Model
```python
python train.py
```

### Evaluating the Model
```python
python evaluate.py
```

## Model Architecture
- **Feature Extraction:** MFCC, Mel Spectrogram, Chroma
- **Transformer Encoder:** Multi-head self-attention layers
- **Fully Connected Layer:** Classification output

## Hyperparameter Tuning
- Adjust learning rate, batch size, and dropout to optimize performance.
- Experiment with different Transformer configurations (e.g., number of heads and layers).

## Evaluation Metrics
- **F1 Score:** Measures classification accuracy.
- **Confusion Matrix:** Visualizes model performance across categories.
- **ROC Curve:** Shows model discrimination capability.

## Future Improvements
- Experiment with CNN-Transformer hybrid models.
- Incorporate additional spectral features for better accuracy.

## License
This project is open-source and available under the MIT License.

## Author
[Your Name]  
[Your Contact or GitHub Profile]

