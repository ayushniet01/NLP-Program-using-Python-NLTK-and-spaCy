📚 NLP Notebooks Repository

A practical collection of Natural Language Processing (NLP) Jupyter Notebooks covering text representation, word embeddings, similarity, classification, sentiment analysis, topic modeling, information extraction, and information retrieval.

This repository is designed for students, beginners, and developers who want to learn NLP concepts through hands-on Python implementations.

🚀 What's Inside?

This repository covers the complete journey from basic text representation to practical NLP applications:

🔤 Bag of Words (BoW)

📊 TF-IDF

🔢 N-Grams

🧠 Word2Vec

🌐 GloVe Embeddings

📐 Cosine Similarity

🚚 Word Mover's Distance (WMD)

🤖 Text Classification

😊 Sentiment Analysis

🧩 Topic Modeling

🔍 Information Extraction

🔎 Information Retrieval

📈 Document Ranking

📚 Notebook Index
1. 🔢 Vectorization & Word Representations
08_Bag_of_Words_(BoW)_Vectorization_and_Representation.ipynb

Learn the fundamentals of Bag-of-Words (BoW) representation and understand how text can be converted into numerical vectors.

09_TF_IDF_Implementation_and_Comparison_with_BoW.ipynb

Implement TF-IDF (Term Frequency-Inverse Document Frequency) and compare it with the Bag-of-Words approach.

10_N_Gram_Model_(Uni_,_Bi_,_Tri_gram)_Generation_from_Corpus.ipynb

Generate different types of N-Grams from a text corpus:

Unigrams

Bigrams

Trigrams

12_Word2Vec_Word_Embeddings_using_Gensim_on_a_Custom_Corpus.ipynb

Train Word2Vec word embeddings using Gensim on a custom text corpus and explore semantic relationships between words.

13_GloVe_Embeddings_Loading_and_Vector_Representation.ipynb

Learn how to load and work with pre-trained GloVe embeddings and represent words as dense vectors.

2. 📐 Document Similarity
11_Cosine_Similarity_Computation_between_Text_Documents.ipynb

Understand and implement Cosine Similarity to measure the similarity between text documents.

14_Text_Similarity_using_Word_Mover's_Distance_(WMD).ipynb

Explore Word Mover's Distance (WMD) for measuring semantic similarity between documents using word embeddings.

3. 🤖 Classification & Sentiment Analysis
15_Text_Classification_using_Naïve_Bayes_SVM_with_TF_IDF.ipynb

Build text classification models using:

Naive Bayes

Support Vector Machine (SVM)

TF-IDF features

16_Sentiment_Analysis_using_TextBlob_and_VADER.ipynb

Perform sentiment analysis using popular lexicon-based NLP tools:

TextBlob

VADER

Analyze whether text expresses positive, negative, or neutral sentiment.

4. 🧠 Topic Modeling & Information Extraction
17_Topic_Modeling_using_Latent_Dirichlet_Allocation_(LDA).ipynb

Discover hidden topics within documents using Latent Dirichlet Allocation (LDA).

18_Topic_Modeling_using_Latent_Semantic_Analysis_(LSA).ipynb

Perform topic modeling using Latent Semantic Analysis (LSA) and Singular Value Decomposition (SVD).

20_Information_Extraction_(IE)_from_Structured_Unstructured_Documents.ipynb

Learn how to extract useful information such as entities, relationships, and metadata from structured and unstructured documents.

5. 🔎 Information Retrieval & Search
21_Information_Retrieval_System_with_Ranking_using_TF_IDF.ipynb

Build a basic Information Retrieval (IR) system that:

Accepts user queries

Compares queries with documents

Calculates relevance scores

Ranks documents

Returns the most relevant results

The system uses TF-IDF and vector similarity for document ranking.

🛠️ Technologies Used

The notebooks are primarily implemented using Python and popular NLP/Data Science libraries.

Technology	Purpose
🐍 Python	Programming Language
📓 Jupyter Notebook	Interactive Development
🔢 NumPy	Numerical Computing
🐼 Pandas	Data Manipulation
🤖 Scikit-learn	Machine Learning
📝 NLTK	Natural Language Processing
🧠 Gensim	Word Embeddings & Topic Modeling
💬 TextBlob	Sentiment Analysis
😊 VADER	Sentiment Analysis
📊 Matplotlib	Data Visualization
🔬 SciPy	Scientific Computing
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

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/your-username/nlp-notebooks.git
cd nlp-notebooks

2. Create a Virtual Environment
python -m venv venv


Activate it:

Windows

venv\Scripts\activate


Linux / macOS

source venv/bin/activate

3. Install Required Libraries
pip install numpy pandas scikit-learn nltk gensim textblob vaderSentiment matplotlib scipy jupyter

4. Start Jupyter Notebook
jupyter notebook


Then open any notebook and run the cells.

🗺️ Recommended Learning Path

If you are new to NLP, follow this order:

Text Representation
        ↓
Bag of Words
        ↓
TF-IDF
        ↓
N-Grams
        ↓
Cosine Similarity
        ↓
Word Embeddings
     ↙       ↘
 Word2Vec   GloVe
     ↓
Text Classification
     ↓
Sentiment Analysis
     ↓
Topic Modeling
   ↙       ↘
 LDA       LSA
     ↓
Information Extraction
     ↓
Information Retrieval

🎯 Learning Outcomes

After completing these notebooks, you should have a practical understanding of:

How computers represent human language

How text is converted into numerical features

How TF-IDF works

How N-Grams capture local word relationships

How Word2Vec and GloVe represent semantic relationships

How to calculate text similarity

How to build basic text classification models

How sentiment analysis works

How topic modeling discovers hidden themes

How information can be extracted from documents

How search engines rank documents based on relevance

💡 NLP Concepts Covered
Text Representation

Learn how raw text is transformed into numerical representations.

Covered:

BoW • TF-IDF • N-Grams

Word Embeddings

Learn how words can be represented as dense vectors containing semantic information.

Covered:

Word2Vec • GloVe

Text Similarity

Measure how similar two pieces of text are.

Covered:

Cosine Similarity • Word Mover's Distance

Text Classification

Build machine learning models for categorizing text.

Covered:

Naive Bayes • SVM • TF-IDF

Sentiment Analysis

Determine the emotional polarity of text.

Covered:

TextBlob • VADER

Topic Modeling

Discover hidden topics within a collection of documents.

Covered:

LDA • LSA • SVD

Information Retrieval

Build a simple search system that retrieves and ranks relevant documents.

Covered:

TF-IDF • Vector Similarity • Document Ranking

🔮 Future Topics

More advanced NLP topics can be added to this repository in the future:

Named Entity Recognition (NER)

Part-of-Speech Tagging

Text Preprocessing Pipelines

Text Summarization

Text Generation

RNNs

LSTMs

GRUs

Transformers

BERT

Hugging Face Transformers

Retrieval-Augmented Generation (RAG)

Large Language Models (LLMs)

🤝 Contributing

Contributions are welcome!

If you would like to improve this repository:

Fork the repository

Create a new branch

Add your notebook or improvements

Commit your changes

Create a Pull Request

⭐ Support

If you find this repository useful for learning NLP, consider giving it a ⭐ Star on GitHub.

It helps others discover the project and motivates further development.

📜 License

This repository is intended for educational and learning purposes.

You can add an open-source license such as the MIT License if you plan to distribute the project publicly.

👨‍💻 Author

AYUSH KUMAR SINGH

A hands-on collection of NLP concepts, implementations, and practical examples using Python.

🚀 Happy Learning & Happy Coding!
