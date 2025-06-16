#  CS5720 – Home Assignment 3
**Course:** Neural Networks and Deep Learning  
**Semester:** Summer 2025  
**University:** University of Central Missouri  
**Student Name:** Gudiseva charan santhosh
**Student id:** 700776700

---

##  Tasks Completed

### 🔹 Task 1: RNN Text Generation
- Implemented an LSTM-based Recurrent Neural Network.
- Trained on a short text sample to predict the next character.
- Demonstrated temperature-based sampling to control randomness of text output.

### 🔹 Task 2: NLP Preprocessing
- Tokenized text using a custom regex-based method.
- Removed English stopwords using NLTK.
- Applied stemming with PorterStemmer.
- Explained:
  - Difference between stemming and lemmatization
  - When removing stopwords is helpful or harmful

### 🔹 Task 3: Named Entity Recognition (NER)
- Used SpaCy (`en_core_web_sm`) to extract named entities.
- Printed entity labels, names, and character offsets.
- Explained difference between NER and POS tagging, with real-world applications.

### 🔹 Task 4: Scaled Dot-Product Attention
- Implemented attention using NumPy:
  - Dot product of Query and Key
  - Scaled by √d
  - Applied softmax to get attention weights
  - Multiplied by Value matrix
- Explained why scaling is important and how attention helps in NLP models.

### 🔹 Task 5: Sentiment Analysis using Transformers
- Used HuggingFace `pipeline("sentiment-analysis")` to classify text.
- Output sentiment label and confidence score.
- Explained BERT vs GPT, and benefits of using pretrained models.

---

### Output Screentshots Examples

## Task 1

![image](https://github.com/user-attachments/assets/8d2e0fd3-4a4a-4cb5-a4a2-50e3590779d4)

## Task 2

![image](https://github.com/user-attachments/assets/44cd3a9e-1aec-487b-91ca-2b57a65326fd)

## Task 3

![image](https://github.com/user-attachments/assets/e3baad32-1abe-41f6-9b91-4e2c986b8400)

## Task 4

![image](https://github.com/user-attachments/assets/a3e7e521-b656-4ef6-a5a0-2ae0cc4ffa23)

## Task 5

![image](https://github.com/user-attachments/assets/16653f96-4f3f-4fdd-918a-6f361176ae03)




##  Requirements

Install these Python libraries before running:

```bash
pip install tensorflow nltk spacy transformers scipy
python -m spacy download en_core_web_sm
