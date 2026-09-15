NLP Practical Programs using Python, NLTK & spaCy

A collection of Natural Language Processing (NLP) practical programs implemented in Python using NLTK and spaCy.

This repository covers fundamental NLP techniques including:

Tokenization
Stemming
Lemmatization
Stop-word removal
POS tagging
Parsing
Chunking
Named Entity Recognition (NER)

🛠️ Technologies Used
Python 3
NLTK (Natural Language Toolkit)
spaCy
Jupyter Notebook / VS Code / PyCharm (optional)

⚙️ Installation

1. Clone the repository
git clone https://github.com/ayushniet01/nlp-practical-programs.git
cd nlp-practical-programs
2. Install the required libraries
pip install nltk spacy
3. Download NLTK resources
Run Python and execute:
import nltk

nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
nltk.download('averaged_perceptron_tagger')
nltk.download('averaged_perceptron_tagger_eng')
4. Download the spaCy English model
python -m spacy download en_core_web_sm

📚 Practical Programs
1. Tokenization
Tokenization divides text into smaller units such as words or sentences.

NLTK Example
from nltk.tokenize import word_tokenize, sent_tokenize

text = "Natural Language Processing is interesting. Python makes NLP easier."

print("Words:", word_tokenize(text))
print("Sentences:", sent_tokenize(text))
spaCy Example
import spacy

nlp = spacy.load("en_core_web_sm")
doc = nlp("Natural Language Processing is interesting.")

for token in doc:
    print(token.text)

2. Stemming
Stemming reduces words to their root or stem form by removing prefixes or suffixes.
from nltk.stem import PorterStemmer

stemmer = PorterStemmer()

words = ["playing", "played", "plays", "studies", "running"]

for word in words:
    print(word, "->", stemmer.stem(word))
Note: Stemming may produce a form that is not a valid dictionary word.

3. Lemmatization
Lemmatization converts a word into its meaningful dictionary or base form.

NLTK Example
from nltk.stem import WordNetLemmatizer

lemmatizer = WordNetLemmatizer()

words = ["running", "studies", "cars", "better"]

for word in words:
    print(word, "->", lemmatizer.lemmatize(word))
spaCy Example
import spacy

nlp = spacy.load("en_core_web_sm")
doc = nlp("The students are studying NLP.")

for token in doc:
    print(token.text, "->", token.lemma_)

4. Stop-word Removal
Stop words are commonly occurring words such as the, is, a, an, and and, which are often removed during NLP preprocessing.

NLTK Example
from nltk.corpus import stopwords
from nltk.tokenize import word_tokenize

text = "This is an example of natural language processing."

stop_words = set(stopwords.words("english"))
words = word_tokenize(text)

filtered_words = [
    word for word in words
    if word.lower() not in stop_words
]

print(filtered_words)
spaCy Example
import spacy

nlp = spacy.load("en_core_web_sm")
doc = nlp("This is an example of natural language processing.")

filtered_words = [
    token.text for token in doc
    if not token.is_stop
]

print(filtered_words)

5. POS Tagging
Part-of-Speech (POS) tagging assigns grammatical labels such as noun, verb, adjective, and adverb to words.
import nltk
from nltk.tokenize import word_tokenize

text = "The quick brown fox jumps over the lazy dog."

words = word_tokenize(text)
pos_tags = nltk.pos_tag(words)

for word, tag in pos_tags:
    print(word, "->", tag)

Common POS Tags
Tag
Meaning
NN
Noun
NNS
Plural noun
VB
Verb
VBD
Past-tense verb
JJ
Adjective
RB
Adverb
PRP
Personal pronoun
DT
Determiner
IN
Preposition

6. Parsing
Parsing analyzes the grammatical structure of a sentence and represents relationships between words.
NLTK Example
import nltk

grammar = nltk.CFG.fromstring("""
S -> NP VP
NP -> DT NN
VP -> VBZ NP
DT -> 'the' | 'a'
NN -> 'boy' | 'ball'
VBZ -> 'plays'
""")

parser = nltk.ChartParser(grammar)

sentence = "the boy plays a ball".split()

for tree in parser.parse(sentence):
    tree.pretty_print()

7. Chunking
Chunking groups words into meaningful phrases such as noun phrases (NP) and verb phrases (VP).
import nltk

sentence = [
    ("The", "DT"),
    ("quick", "JJ"),
    ("brown", "JJ"),
    ("fox", "NN"),
    ("jumps", "VBZ")
]

grammar = "NP: {<DT>?<JJ>*<NN>}"

chunk_parser = nltk.RegexpParser(grammar)
tree = chunk_parser.parse(sentence)

tree.pretty_print()

8. Named Entity Recognition (NER)
Named Entity Recognition identifies entities such as:
Person names
Organizations
Locations
Dates
Money
Companies
spaCy Example
import spacy

nlp = spacy.load("en_core_web_sm")

text = "Elon Musk founded SpaceX in the United States."

doc = nlp(text)

for ent in doc.ents:
    print(ent.text, "->", ent.label_)

📁 Suggested Project Structure
NLP-Practical-Programs/
│
├── README.md
├── requirements.txt
│
├── 01_tokenization.py
├── 02_stemming.py
├── 03_lemmatization.py
├── 04_stopword_removal.py
├── 05_pos_tagging.py
├── 06_parsing.py
├── 07_chunking.py
└── 08_ner.py
Alternatively, if each practical is in its own folder:
NLP-Practical-Programs/
│
├── README.md
├── Tokenization/
├── Stemming/
├── Lemmatization/
├── Stopword-Removal/
├── POS-Tagging/
├── Parsing/
├── Chunking/
└── NER/
▶️ How to Run
For a Python program:
python 01_tokenization.py
Replace the filename with the practical you want to execute.
For Jupyter Notebook:
jupyter notebook
Then open the required .ipynb file.

🎯 Learning Objectives
After completing these practicals, you should be able to:
Understand basic NLP preprocessing.
Split text into words and sentences.
Apply stemming and lemmatization.
Remove stop words.
Perform Part-of-Speech tagging.
Understand basic syntactic parsing.
Extract phrases using chunking.
Identify named entities from text.
Work with both NLTK and spaCy.

🔄 NLP Pipeline
A typical NLP workflow can be represented as:
Raw Text
   ↓
Tokenization
   ↓
Stop-word Removal
   ↓
Stemming / Lemmatization
   ↓
POS Tagging
   ↓
Parsing / Chunking
   ↓
Named Entity Recognition
   ↓
Processed Text / Information

📦 requirements.txt
Create a requirements.txt file containing:
nltk
spacy
Install all dependencies using:
pip install -r requirements.txt
Then install the spaCy English model:
python -m spacy download en_core_web_sm
👨‍💻 Author
AYUSH KUMAR SINGH 
GitHub: https://github.com/ayushniet01 

Replace the author details and links with your own information before publishing.

⭐ Support
If you find this repository useful for learning NLP, consider giving it a star ⭐ on GitHub.

📄 License
This project is intended for educational and practical learning purposes and can be used for coursework and personal learning.