![performence plt](https://pkseeg.com/project/nlp-disaster-tweets/featured_hu1fab531a599ec64148ba8b7009fdb0ff_507366_720x0_resize_lanczos_2.png)

# Predicting Disaster Tweets

This project focuses on classifying tweets as either disaster-related or not, using machine learning models. The dataset used is from a Kaggle competition, and several deep learning models like RNN, Bi-GRU, Bi-LSTM, and ALBERT have been implemented for classification.

## Prerequisites

1. **Ensure you have Python 3.11.9 installed** on your machine.

2. **Set up a Virtual Environment** (optional, but recommended):
   ```bash
   python3.11 -m venv venv
   ```

   - For Linux/MacOS:
     ```bash
     source venv/bin/activate
     ```
   - For Windows:
     ```bash
     .\venv\Scripts\activate
     ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Model Performance

| Model    | Accuracy | Precision | Recall | F1 Score | Batch Size |
|----------|----------|-----------|--------|----------|------------|
| RNN      | 0.773    | 0.748     | 0.732  | 0.740    | 32         |
| Bi-GRU   | 0.756    | 0.742     | 0.685  | 0.712    | 32         |
| Bi-LSTM  | 0.783    | 0.716     | 0.842  | 0.774    | 32         |
| ALBERT   | 0.799    | 0.812     | 0.708  | 0.757    | 32         |

## Model Performance Visualization
Here is a plot visualizing the performance metrics of the models used:

![performence plt](https://i.imgur.com/74GcI2K.png)

## Overview of Models Used

- **RNN**: Recurrent Neural Network, a basic model for sequence data.
- **Bi-GRU**: Bidirectional Gated Recurrent Unit, a more advanced model with bidirectional layers.
- **Bi-LSTM**: Bidirectional Long Short-Term Memory network, known for capturing long-term dependencies.
- **ALBERT**: A transformer-based model that provides excellent accuracy with lower resource usage.

## Project Structure

- `disaster_tweets.ipynb`: Jupyter notebook containing the model training and evaluation.
- `train.csv`: Dataset used for training.
- `requirements.txt`: File listing the Python dependencies for the project.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Muntasir-Arin/Predicting-disaster-tweets.git
   ```

2. Follow the instructions in the **Prerequisites** section to set up your environment and install dependencies.

3. Run the notebook or script to train and evaluate the models.

## License

This project is open source and available under the [MIT License](LICENSE).
