# Intent Analysis

This project focuses on predicting user intents based on a sequence of UI actions using deep learning. The model takes a sliding window of action logs and predicts the most likely intent for the next action.

## 📁 Project Structure

- `excel_action_log.csv`: Input dataset containing action types and keys/buttons used.
- `Intent_Analysis.ipynb`: Jupyter Notebook that handles preprocessing, encoding, modeling, and evaluation.
- Trained on sequential user interaction logs to learn underlying patterns and predict future intent.

## 🧠 Methodology

1. **Data Preprocessing**
   - Combines `Action Type` and `Key/Button` into a single string.
   - Constructs fixed-size sequences using a sliding window approach.

2. **Label Encoding**
   - Actions and intents are label-encoded for numerical modeling.

3. **Modeling**
   - Uses TensorFlow/Keras to build an LSTM-based neural network for sequence modeling.

4. **Evaluation**
   - Measures prediction accuracy on a test split of the dataset.

## 🛠 Requirements

pip install pandas numpy scikit-learn tensorflow
# Intent Analysis

This project focuses on predicting user intents based on a sequence of UI actions using deep learning. The model takes a sliding window of action logs and predicts the most likely intent for the next action.

## 📁 Project Structure

- `excel_action_log.csv`: Input dataset containing action types and keys/buttons used.
- `Intent_Analysis.ipynb`: Jupyter Notebook that handles preprocessing, encoding, modeling, and evaluation.
- Trained on sequential user interaction logs to learn underlying patterns and predict future intent.

## 🧠 Methodology

1. **Data Preprocessing**
   - Combines `Action Type` and `Key/Button` into a single string.
   - Constructs fixed-size sequences using a sliding window approach.

2. **Label Encoding**
   - Actions and intents are label-encoded for numerical modeling.

3. **Modeling**
   - Uses TensorFlow/Keras to build an LSTM-based neural network for sequence modeling.

4. **Evaluation**
   - Measures prediction accuracy on a test split of the dataset.
