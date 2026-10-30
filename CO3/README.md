# Advanced Natural Language Processing (NLP) Experiments

This repository contains advanced NLP experiments using Transformer models, BERT, GPT-2, Hugging Face, machine learning, and sequence modeling techniques. These experiments explore text classification, sentence embeddings, text generation, named entity recognition, machine translation, text summarization, and document processing.

## 📚 Experiments Included

| No. | Experiment | Description |
|---|---|---|
| 24 | Fine-Tuning BERT for Text Classification | Fine-tuning a pretrained BERT model for text classification using Hugging Face. |
| 25 | Sentence Embeddings using BERT and GPT-2 | Generating sentence representations using transformer-based models. |
| 26 | Text Generation using GPT-2 | Generating text using GPT-2 on a custom dataset. |
| 27 | Named Entity Recognition using Transformers (BERT) | Identifying entities such as names, locations, and organizations in text. |
| 28 | Machine Translation using MarianMT or T5 | Translating text using pretrained Hugging Face transformer models. |
| 29 | Text Summarization using BART or T5 | Generating concise summaries from longer text documents. |
| 30 | Text Summarization using BART or T5 | Exploring another implementation of transformer-based text summarization. |
| 31 | Automatic Document Classification and Separation using ML | Classifying documents and separating them into categories using machine learning. |
| 32 | Hybrid Probabilistic + FSM-Based Sequence Modeling | Combining probabilistic methods and Finite State Machines (FSM) for document-boundary detection and sequence modeling. |

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Hugging Face Transformers
- BERT
- GPT-2
- BART
- T5
- MarianMT
- PyTorch
- TensorFlow / Keras (where required)
- scikit-learn
- NumPy and pandas

## 🚀 Installation and Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

Replace the placeholders with your actual GitHub repository URL and folder name.

### 2. Install Dependencies

```bash
pip install jupyter transformers torch tensorflow scikit-learn numpy pandas sentencepiece
```

Some notebooks may require additional packages depending on the model and implementation.

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the desired `.ipynb` file and execute the cells sequentially.

## 📂 Project Structure

```text
Advanced-NLP-Experiments/
├── 24_Fine_Tuning_BERT_for_text_classification_using_Hugging_Face.ipynb
├── 25_Sentence_Embeddings_using_BERT_and_GPT_2.ipynb
├── 26_Text_Generation_using_GPT_2_on_a_custom_dataset.ipynb
├── 27_Named Entity Recognition using Transformers(BERT).ipynb
├── 28_Machine Translation using MarianMT or T5 (Hugging Face).ipynb
├── 29_Text Summarization using BART or T5.ipynb
├── 30_Text Summarization using BART or T5.ipynb
├── 31_Automatic Document Classification and Separation using ML.ipynb
└── 32_Hybrid Probabilistic + FSM-Based Sequence Modeling for document boundary detection.ipynb
```

*Note: The filename of Experiment 32 is shortened in the screenshot. Update it to match the exact filename in your repository.*

## 🎯 Learning Objectives

- Understand transformer-based NLP models.
- Fine-tune pretrained models for text classification.
- Generate sentence embeddings and text using language models.
- Perform named entity recognition.
- Implement machine translation and text summarization.
- Apply machine learning to document classification.
- Explore hybrid probabilistic and FSM-based sequence modeling.

## 📝 Notes

- Some models download pretrained weights from Hugging Face when first used.
- A suitable internet connection may be required for downloading models and datasets.
- Large transformer models may require significant RAM or GPU resources.
- Update dataset paths and model configurations according to your environment.
- Follow the setup instructions provided in each notebook.

## 👨‍💻 Author

**AYUSH KUMAR SINGH**

## 📄 License

This project is intended for educational and learning purposes. Add an appropriate open-source license if you plan to distribute or reuse this project publicly.
