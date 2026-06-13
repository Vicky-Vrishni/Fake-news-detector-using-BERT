# Fake-news-detector-using-BERT
A Fake News Detector built using BERT (bert-base-uncased), a pre-trained  NLP model. The system classifies news articles as Real or Fake with 95%  accuracy. Trained on a labeled dataset of 6,335 articles using PyTorch  and Hugging Face Transformers. Includes exploratory data analysis with  word clouds, histograms, and confusion matrix heatmap.

## Overview
This project detects whether a news article is Real or Fake using 
BERT (Bidirectional Encoder Representations from Transformers), 
a pre-trained NLP model by Google. The model is fine-tuned on a 
labeled news dataset and achieves 95.03% accuracy.

## Dataset
- File: news.csv
- Total Records: 6,335
- Labels: REAL (1) and FAKE (0)
- Source: Kaggle

## Technologies Used
- Python
- BERT (bert-base-uncased)
- PyTorch
- Hugging Face Transformers
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- WordCloud

## Project Structure
- Data Loading and Preprocessing
- Exploratory Data Analysis (Bar Chart, Histogram, Word Clouds)
- Train-Test Split (80-20)
- BERT Tokenization
- Model Training (3 Epochs)
- Evaluation (Accuracy, Classification Report, Confusion Matrix)
- Prediction Function

## Results
| Metric    | Value  |
|-----------|--------|
| Accuracy  | 95.03% |
| Precision | 0.95   |
| Recall    | 0.95   |
| F1-Score  | 0.95   |

## Training Loss
| Epoch | Loss   |
|-------|--------|
| 1     | 0.2050 |
| 2     | 0.0667 |
| 3     | 0.0328 |

## How to Run
1. Clone this repository
2. Install dependencies:
   pip install transformers torch pandas scikit-learn matplotlib seaborn wordcloud
3. Place news.csv in the same folder
4. Open Fake_news_detector_project.ipynb in Jupyter Notebook or Google Colab
5. Run all cells in order

## Author
- Name: Vikky Kumar
- College: Guru Jambheshwar University of Science and Technology, Hisar, Haryana
- Branch & Year: CSE, 3rd Year
- Email: skvickyyadav942@gmail.com
