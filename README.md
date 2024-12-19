# TensorFlow-based SMS Spam Filter

## Overview
The TensorFlow-based SMS Spam Filter is a machine learning project designed to identify and filter out spam messages from SMS communications. By leveraging the capabilities of TensorFlow, this project implements a text classification model to distinguish between spam and non-spam (ham) messages efficiently.

---

## Features
- Real-time Spam Detection: Classifies SMS messages into spam or ham categories.
- Pre-trained Model: Uses TensorFlow for deep learning-based classification.
- Scalable Solution: Can be adapted for large-scale SMS filtering in real-world applications.


---

## Dataset
The model is trained on a dataset containing SMS messages labelled as either spam or ham. Key attributes include:
- Message(v2): The SMS text content.
- Label(v1): Spam or ham.

Ensure the dataset is in CSV format with the necessary preprocessing applied before training the model.

---

## Installation
### Prerequisites
- Python 3.8+
- TensorFlow 2.0+

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/Athyy7/TensorFlow-based-SMS-Spam-Filter
   ```
2. Navigate to the project directory:
   ```bash
   cd TensorFlow_based_SMS_Spam_Filter
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage
### Training the Model
1. Prepare the dataset in the `/data` folder.
2. Open the Jupyter notebook `notebooks/SMS_Spam_Classifier.ipynb`.
3. Run all cells to preprocess data, train the model, and evaluate its performance.

---

## Model Architecture
- Embedding Layer: Converts text tokens into dense vector representations.
- LSTM Layer: Captures contextual information within sequences.
- Dense Layers: Outputs the classification probabilities.

---

## Evaluation Metrics
The model's performance is evaluated using:
- Accuracy: Percentage of correctly classified messages.
- Precision: Fraction of relevant spam messages among those classified as spam.
- Recall: Fraction of spam messages correctly identified.
- F1 Score: Harmonic mean of precision and recall.

---

## Results
### Performance Summary
| Metric    | Score     |
|-----------|-----------|
| Accuracy  | 98.5%     |
| Precision | 97.8%     |
| Recall    | 96.9%     |
| F1 Score  | 97.3%     |


---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Contact
For inquiries or feedback, feel free to reach out:
- Email: atharav.shivhare009@gmail.com
- GitHub: Athyy7 (https://github.com/Athyy7)
