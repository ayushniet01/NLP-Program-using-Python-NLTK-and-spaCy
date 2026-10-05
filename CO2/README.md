📚 NLP Notebooks Repository

Welcome to the NLP Notebooks Repository — a curated collection of hands-on Jupyter Notebooks covering fundamental and practical concepts in Natural Language Processing (NLP).

This repository is designed as a learning resource for understanding how textual data can be transformed, represented, analyzed, classified, and searched using classical NLP techniques and machine learning approaches.

From Bag-of-Words and TF-IDF to Word2Vec, GloVe, sentiment analysis, topic modeling, information extraction, and information retrieval, these notebooks provide practical implementations of important NLP concepts.

🎯 What You'll Learn

By working through these notebooks, you will learn how to:

Convert text into numerical representations

Build Bag-of-Words and TF-IDF representations

Generate unigrams, bigrams, and trigrams

Work with Word2Vec and GloVe embeddings

Calculate similarity between text documents

Perform text classification

Analyze sentiment using lexicon-based approaches

Discover hidden topics in documents

Extract useful information from structured and unstructured text

Build a basic information retrieval and document-ranking system

📖 Index of Notebooks
1. 🔢 Vectorization & Word Representations
Notebook	Description
08_Bag_of_Words_(BoW)_Vectorization_and_Representation.ipynb	Learn the fundamentals of Bag-of-Words text representation and vocabulary building.
09_TF_IDF_Implementation_and_Comparison_with_BoW.ipynb	Implement TF-IDF vectorization and compare it with Bag-of-Words representations.
10_N_Gram_Model_(Uni_,_Bi_,_Tri_gram)_Generation_from_Corpus.ipynb	Generate word-level unigrams, bigrams, and trigrams from a text corpus.
12_Word2Vec_Word_Embeddings_using_Gensim_on_a_Custom_Corpus.ipynb	Train Word2Vec word embeddings using Gensim on a custom corpus.
13_GloVe_Embeddings_Loading_and_Vector_Representation.ipynb	Load pre-trained GloVe embeddings and perform vector-based operations.
2. 📐 Document Similarity & Clustering
Notebook	Description
11_Cosine_Similarity_Computation_between_Text_Documents.ipynb	Compute cosine similarity between document vectors and understand text similarity.
14_Text_Similarity_using_Word_Mover's_Distance_(WMD).ipynb	Measure semantic similarity between documents using Word Mover's Distance and word embeddings.
3. 🤖 Classification & Sentiment Analysis
Notebook	Description
15_Text_Classification_using_Naïve_Bayes_SVM_with_TF_IDF.ipynb	Build text classification models using Naive Bayes and Support Vector Machines with TF-IDF features.
16_Sentiment_Analysis_using_TextBlob_and_VADER.ipynb	Perform sentiment analysis using TextBlob and VADER.
4. 🧠 Topic Modeling & Information Extraction
Notebook	Description
17_Topic_Modeling_using_Latent_Dirichlet_Allocation_(LDA).ipynb	Discover hidden topics in a collection of documents using Latent Dirichlet Allocation.
18_Topic_Modeling_using_Latent_Semantic_Analysis_(LSA).ipynb	Perform topic extraction using Latent Semantic Analysis and Singular Value Decomposition.
20_Information_Extraction_(IE)_from_Structured_Unstructured_Documents.ipynb	Extract useful entities, relationships, and metadata from structured and unstructured documents.
5. 🔎 Information Retrieval & Search
Notebook	Description
21_Information_Retrieval_System_with_Ranking_using_TF_IDF.ipynb	Build an information retrieval system that ranks documents based on query relevance using TF-IDF and vector similarity.
🛠️ Technologies & Libraries

The notebooks make use of several popular Python libraries and NLP tools, including:

Python

Jupyter Notebook

NumPy

Pandas

Scikit-learn

NLTK

Gensim

TextBlob

VADER

Matplotlib

SciPy

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/your-username/nlp-notebooks.git
cd nlp-notebooks

2. Create a Virtual Environment
python -m venv venv


Activate the environment:

Windows:

venv\Scripts\activate


macOS/Linux:

source venv/bin/activate

3. Install Dependencies
pip install numpy pandas scikit-learn nltk gensim textblob vaderSentiment matplotlib scipy jupyter

4. Launch Jupyter Notebook
jupyter notebook


Open the notebook you want to explore and run the cells sequentially.

🗺️ Recommended Learning Path

If you are new to NLP, the notebooks can be studied in the following order:

Text Preprocessing
       ↓
Bag-of-Words
       ↓
TF-IDF
       ↓
N-Grams
       ↓
Cosine Similarity
       ↓
Word Embeddings
   ↙         ↘
Word2Vec    GloVe
       ↓
Text Classification
       ↓
Sentiment Analysis
       ↓
Topic Modeling
   ↙         ↘
  LDA        LSA
       ↓
Information Extraction
       ↓
Information Retrieval


This progression moves from basic text representation toward more advanced NLP applications.

💡 Key NLP Concepts Covered
Text Representation

Learn how raw text can be converted into numerical vectors that machine learning algorithms can process.

Techniques covered:

Bag-of-Words

TF-IDF

N-Grams

Word Embeddings

Semantic Similarity

Explore different ways of determining how similar two pieces of text are.

Methods covered:

Cosine Similarity

Word Mover's Distance

Word Embeddings

Text Classification

Learn how machine learning models can categorize text into predefined classes.

Models covered:

Naive Bayes

Support Vector Machines

TF-IDF-based classification

Sentiment Analysis

Understand how NLP systems can determine the sentiment expressed in text.

Tools covered:

TextBlob

VADER

Topic Modeling

Discover hidden themes and topics within collections of documents.

Methods covered:

Latent Dirichlet Allocation (LDA)

Latent Semantic Analysis (LSA)

Singular Value Decomposition (SVD)

Information Retrieval

Build a basic search system capable of matching user queries against documents and ranking results according to relevance.

📂 Repository Structure
NLP-Notebooks/
│
├── 08_Bag_of_Words_(BoW)_Vectorization_and_Representation.ipynb
├── 09_TF_IDF_Implementation_and_Comparison_with_BoW.ipynb
├── 10_N_Gram_Model_(Uni_,_Bi_,_Tri_gram)_Generation_from_Corpus.ipynb
├── 11_Cosine_Similarity_Computation_between_Text_Documents.ipynb
├── 12_Word2Vec_Word_Embeddings_using_Gensim_on_a_Custom_Corpus.ipynb
├── 13_GloVe_Embeddings_Loading_and_Vector_Representation.ipynb
├── 14_Text_Similarity_using_Word_Mover's_Distance_(WMD).ipynb
├── 15_Text_Classification_using_Naïve_Bayes_SVM_with_TF_IDF.ipynb
├── 16_Sentiment_Analysis_using_TextBlob_and_VADER.ipynb
├── 17_Topic_Modeling_using_Latent_Dirichlet_Allocation_(LDA).ipynb
├── 18_Topic_Modeling_using_Latent_Semantic_Analysis_(LSA).ipynb
├── 20_Information_Extraction_(IE)_from_Structured_Unstructured_Documents.ipynb
├── 21_Information_Retrieval_System_with_Ranking_using_TF_IDF.ipynb
│
└── README.md

👨‍💻 Who Is This Repository For?

This repository is useful for:

Students learning Natural Language Processing

Beginners exploring NLP with Python

Machine Learning and Data Science learners

Developers building NLP applications

Anyone looking for practical NLP implementations

Students preparing NLP concepts for interviews and projects

⭐ Topics at a Glance
Area	Techniques
Text Representation	BoW, TF-IDF, N-Grams
Word Embeddings	Word2Vec, GloVe
Similarity	Cosine Similarity, WMD
Classification	Naive Bayes, SVM
Sentiment	TextBlob, VADER
Topic Modeling	LDA, LSA, SVD
Information Extraction	Entity & Metadata Extraction
Information Retrieval	TF-IDF, Document Ranking
📌 Future Additions

Potential topics that can be added to expand this repository:

Text preprocessing pipelines

Named Entity Recognition (NER)

Part-of-Speech (POS) tagging

Text summarization

Text generation

Sequence-to-sequence models

Recurrent Neural Networks (RNNs)

LSTMs and GRUs

Transformer architectures

BERT and other pretrained language models

Hugging Face Transformers

Retrieval-Augmented Generation (RAG)

🤝 Contributing

Contributions are welcome!

If you have improvements, additional notebooks, examples, or corrections, feel free to:

Fork the repository

Create a new branch

Add your improvements

Commit your changes

Open a Pull Request

📜 License

This project is intended for educational and learning purposes. Add an appropriate open-source license such as MIT if you plan to distribute the repository publicly.

⭐ If You Find This Useful

If this repository helps you learn NLP, consider giving it a ⭐ star and sharing it with others who are learning Natural Language Processing.

Happy Learning & Happy Coding! 🚀
