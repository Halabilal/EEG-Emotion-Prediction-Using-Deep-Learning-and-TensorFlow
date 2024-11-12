# EEG-Emotion-Prediction-Using-Deep-Learning-and-TensorFlow
## Objective
### Predict the emotional state (positive, neutral, negative) of subjects based on EEG brainwave data collected while they watched movie clips.
## Dataset
### The "Feeling Emotions" EEG dataset, consisting of 2,132 samples from two subjects, recorded with a Muse EEG headband. The dataset includes both statistical features and FFT-transformed data from four EEG channels (TP9, AF7, AF8, TP10).
## Methodology
### Built and trained a Recurrent Neural Network (RNN) model using TensorFlow to capture temporal patterns in EEG data. Key steps:
#### •	Data preprocessing, including label encoding and a 70/30 train-test split.
#### •	Model architecture: a GRU-based RNN with 256 units followed by a dense softmax layer for classification.
#### •	Training setup: The model was compiled with Adam optimizer, sparse categorical cross-entropy loss, and early stopping to prevent overfitting.
## Results
### The TensorFlow model achieved a test accuracy of 94.4%. Evaluation metrics indicate balanced performance across emotional states, with the highest accuracy for neutral states.
### Key Insights
#### •	The TensorFlow RNN effectively captured the temporal structure of EEG signals for emotion classification.
#### •	Confusion matrix analysis showed strong precision and recall, supporting the model's robustness across different emotional classes.
