# Toxic Comment Classification with Deep Learning

This project classifies text-based comments into categories like toxic, moderately toxic, severely toxic, racist, etc., using a supervised learning approach with multi-binary labels.

## Workflow

### 1. Install Dependencies and Load Data

### 2. Preprocessing
- **Tokenization:** Convert comments to integer sequences using a text vectorization layer.
- **Text Vectorization Layer:** Maps text to integer sequences, learning vocabulary from the dataset.

### 3. Create Sequential Model
- **Embedding Layer:** Converts tokens to dense vectors, learning word attributes.
- **LSTM Layers:** Capture long-term dependencies; bidirectional LSTM enhances context understanding.
- **Output Layer:** Uses Sigmoid activation for binary label outputs.

### 4. Predictions
- Classify new comments into toxicity categories.

### 5. Evaluation
- Metrics: Precision, recall, accuracy for model performance.

### 6. Testing and Gradio App
- Validate with unseen data.
- Gradio app for user interaction.

## Features
- Multi-output model with bidirectional LSTM and Sigmoid activation.
- Gradio app for easy testing.
