# AI-Powered Mental Health Detection System 

##  Project Overview
This project focuses on the detection of early signs of depression from social media text (Reddit data). By comparing traditional Machine Learning baselines against State-of-the-Art Transformer models, this research aims to build a robust, high-precision screening tool for mental health triage.

** [Read the Mini-Research Paper (PDF)](./mini_research_paper.pdf)**

##  Key Results
| Model | Accuracy | Notes |
|-------|----------|-------|
| **BERT (Fine-tuned)** | **>99%** | Best performance, high context awareness |
| **RoBERTa** | **>99%** | Comparable to BERT, robust to noise |
| LSTM | ~94% | Good baseline, but struggles with long context |
| Logistic Regression | ~90% | Baseline |

##  Tech Stack
- **Language:** Python
- **Libraries:** PyTorch, Hugging Face Transformers, NLTK, Scikit-learn, Pandas.
- **Techniques:** Transfer Learning, Tokenization, Word Embeddings (GloVe), Stop-word removal.

##  Methodology
1. **Preprocessing:** Cleaning unstructured Reddit posts (tokenization, lemmatization).
2. **Feature Engineering:** TF-IDF for baselines vs. Deep Contextual Embeddings for Transformers.
3. **Training:** Fine-tuning pre-trained BERT/RoBERTa models on the depression dataset.
4. **Evaluation:** Benchmarked using Accuracy, F1-Score, and Recall.

##  Ethical Considerations
This model is designed for research and triage support, not as a replacement for clinical diagnosis. Data anonymization and bias mitigation were central to the development process.
