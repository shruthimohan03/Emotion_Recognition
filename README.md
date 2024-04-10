# Emotion_Recognition
Unveiling the ability to comprehend sentiments embedded within text data.

Dataset Used: MELD-A Multimodal Multi-Party Dataset for Emotion Recognition in Conversation (https://github.com/declare-lab/MELD)

About the Dataset: 
- Transcripts from the popular TV sitcom Friends with over 1 million labeled instances of dialogue (we used only a subset of this).
- Labeled with emotions like neutral, joy, surprise, anger, fear, sadness and disgust.

Static Models with Embeddings:
- Logistic Regression: Baseline static model for text classification.
- Embeddings Used: BOW, TF-IDF, CBOW, Skipgram embeddings explored.
- Evaluation: Accuracy, F1-score compared across embeddings.

Selecting the Main Model:
- BOW Superiority: Bag of Words embedding outperformed others.
- Neural Network Architecture for intensive training

Neural Network Architecture:
- Non-linear Modeling: Captures complex relationships in text data.
- Large Data Handling: Scales to process massive text corpora.
- Flexible Architecture: Incorporates various input features beyond text.
- High Accuracy: Model achieved 84% accuracy on test set.
  
Significance:
Emotion recognition enables advanced sentiment analysis for social media, customer feedback, mental health applications.
