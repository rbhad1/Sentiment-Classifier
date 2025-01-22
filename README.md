## Sentiment Classifier
This project involves fine-tuning Google's BERT model to classify statements from the Federal Reserve (FED) communications (e.g., press conferences, speeches) as dovish, hawkish, neutral, or irrelevant with the goal of infering the FED's monetary policy stance.

**Key Features:**
• Model: Fine-tuned Google's BertForSequenceClassification (bert-base-uncased) using a custom training loop
• Libraries: PyTorch, Hugging Face, scikit-learn, and Matplotlib for model training, evaluation, and visualization
• Dataset: Data from data.csv consisting of statements from FED communications

**Results:**
The model’s performance showed a promising classification accuracy (accuracy: ..), as visualized in the training and validation loss curves:

<img width="298" alt="image" src="https://github.com/user-attachments/assets/6f44a125-b676-40c3-a25e-4aa1e8ff7317" />

Future Direction:
• **Data Expansion**: Increase the datast and train model on mor etesting data to improve accuracy 
• **Model Comparison**: Fine-tuning other LLMs and compare their performance to identify the best model for this task
• **Investment** **Strategy**: Explore how FED sentiment can be applied to optimize investment strategies and determine if there is a correlation between market movement and FED sentiment
