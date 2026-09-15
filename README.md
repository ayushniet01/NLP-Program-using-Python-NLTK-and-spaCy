# NLP Unit 1 Programs

A collection of basic **Natural Language Processing (NLP)** practical programs implemented using **Python, NLTK, and spaCy**.

This repository contains six practical programs covering fundamental NLP techniques including **Tokenization, Stemming, Lemmatization, Stop-word Removal, Part-of-Speech (POS) Tagging, Parsing, Chunking, and Named Entity Recognition (NER).**

---

## 📚 Programs Included

### 1. Tokenization

**Folder:** `01_Tokenization`

Tokenization is the process of breaking text into smaller units called **tokens**, such as sentences and words.

#### Technologies Used

* Python
* NLTK
* spaCy

#### Concepts Covered

* Sentence Tokenization
* Word Tokenization
* Text Segmentation

#### File

`tokenization.ipynb`

---

### 2. Stemming and Lemmatization

**Folder:** `02_Stemming_Lemmatization`

This program demonstrates two techniques used to obtain the base or root form of words.

**Stemming** removes word endings to obtain a root form. It may sometimes produce a non-dictionary word.

**Lemmatization** converts a word into its meaningful dictionary base form.

#### Technologies Used

* Python
* NLTK Porter Stemmer
* NLTK WordNet Lemmatizer

#### Concepts Covered

* Porter Stemming
* WordNet Lemmatization
* Root Word Extraction
* Base Word Extraction

#### File

`stemming_lemmatization.ipynb`

---

### 3. Stop-word Removal

**Folder:** `03_Stopword_Removal`

Stop words are commonly occurring words that may provide little useful information for certain NLP tasks.

#### Examples

```text
the
is
a
an
and
of
```

This program demonstrates how stop words can be identified and removed from a document using NLTK.

#### Technologies Used

* Python
* NLTK

#### Concepts Covered

* Word Tokenization
* Stop-word Identification
* Stop-word Removal
* Text Preprocessing

#### File

`stopword_removal.ipynb`

---

### 4. Part-of-Speech (POS) Tagging

**Folder:** `04_POS_Tagging`

Part-of-Speech tagging assigns a grammatical category to each word in a sentence.

#### Examples

* Noun
* Verb
* Adjective
* Adverb
* Preposition
* Determiner
* Pronoun

#### Technologies Used

* Python
* NLTK

#### Concepts Covered

* Word Tokenization
* POS Tagging
* Grammatical Categories
* Linguistic Analysis

#### File

`pos_tagging.ipynb`

---

### 5. Parsing and Chunking

**Folder:** `05_Parsing_Chunking`

This program demonstrates syntactic analysis using **regular-expression-based chunking** and **dependency parsing**.

#### Technologies Used

* Python
* NLTK
* spaCy

#### Concepts Covered

* POS Tagging
* Regular Expression Chunking
* Noun Phrase Chunking
* Dependency Parsing
* Grammatical Relationships
* Syntactic Analysis

#### File

`parsing_chunking.ipynb`

---

### 6. Named Entity Recognition (NER)

**Folder:** `06_Named_Entity_Recognition`

Named Entity Recognition (NER) identifies and classifies important named entities from text.

#### Examples of Entities

* Person
* Organization
* Location
* Date
* Money
* Geopolitical Entity

#### Technologies Used

* Python
* spaCy

#### Concepts Covered

* Named Entity Recognition
* Entity Classification
* Entity Labels
* Information Extraction

#### File

`ner.ipynb`

---

## 🛠️ Technologies Used

| Technology       | Purpose                     |
| ---------------- | --------------------------- |
| Python 3         | Programming Language        |
| NLTK             | Natural Language Processing |
| spaCy            | NLP and Linguistic Analysis |
| Jupyter Notebook | Running Practical Programs  |

---

## ⚙️ Installation

Make sure **Python 3** is installed on your system.

### 1. Clone the Repository

```bash
git clone https://github.com/ayushniet01/NLP-Unit-1-Programs.git
```

Navigate to the project directory:

```bash
cd NLP-Unit-1-Programs
```

### 2. Install Required Libraries

```bash
pip install nltk spacy
```

### 3. Download spaCy English Language Model

```bash
python -m spacy download en_core_web_sm
```

### 4. NLTK Resources

The required NLTK resources are downloaded within the respective practical programs.

These may include:

* `punkt`
* `punkt_tab`
* `stopwords`
* `averaged_perceptron_tagger_eng`
* `wordnet`
* `omw-1.4`

---

## ▶️ How to Run

The practical programs are provided as **Jupyter Notebook (`.ipynb`) files**.

Open the required notebook using a compatible notebook environment and execute the cells sequentially.

### Example

```text
01_Tokenization/tokenization.ipynb
```

Similarly, open the notebooks available in the remaining folders to execute the other practicals.

---

## 📂 Repository Structure

```text
NLP-Unit-1-Programs/
│
├── 01_Tokenization/
│   └── tokenization.ipynb
│
├── 02_Stemming_Lemmatization/
│   └── stemming_lemmatization.ipynb
│
├── 03_Stopword_Removal/
│   └── stopword_removal.ipynb
│
├── 04_POS_Tagging/
│   └── pos_tagging.ipynb
│
├── 05_Parsing_Chunking/
│   └── parsing_chunking.ipynb
│
├── 06_Named_Entity_Recognition/
│   └── ner.ipynb
│
└── README.md
```

---

## 🎯 Learning Objectives

Through these practical programs, the following fundamental NLP concepts are demonstrated:

1. **Sentence Tokenization**
2. **Word Tokenization**
3. **Stemming**
4. **Lemmatization**
5. **Stop-word Removal**
6. **Part-of-Speech (POS) Tagging**
7. **Parsing**
8. **Chunking**
9. **Named Entity Recognition (NER)**

---

## 🔄 NLP Processing Workflow

The practicals cover several important stages of Natural Language Processing:

```text
Raw Text
   │
   ▼
Tokenization
   │
   ▼
Text Preprocessing
   │
   ├── Stemming
   │
   ├── Lemmatization
   │
   └── Stop-word Removal
   │
   ▼
POS Tagging
   │
   ▼
Parsing & Chunking
   │
   ▼
Named Entity Recognition
   │
   ▼
Processed & Analyzed Text
```

---

## 🎓 Course Outcome

After completing these practicals, learners will have a basic understanding of how natural language can be processed and analyzed using Python-based NLP libraries.

These programs demonstrate the progression from **raw text processing to linguistic analysis, syntactic analysis, and entity identification**.

The practicals also provide hands-on experience with popular NLP libraries such as **NLTK and spaCy**.

---

## 📖 Practical Topics Summary

| No. | Practical                | Main Concepts                  |
| --- | ------------------------ | ------------------------------ |
| 01  | Tokenization             | Sentence and Word Tokenization |
| 02  | Stemming & Lemmatization | Root and Base Word Extraction  |
| 03  | Stop-word Removal        | Text Preprocessing             |
| 04  | POS Tagging              | Grammatical Categories         |
| 05  | Parsing & Chunking       | Syntax and Dependency Analysis |
| 06  | NER                      | Named Entity Identification    |

---

## 👨‍💻 Author

**Ayush Kumar Singh**

GitHub: [ayushniet01](https://github.com/ayushniet01)

---

## 📌 Note

This repository is created for **academic and practical learning purposes**.

It demonstrates fundamental Natural Language Processing concepts using **Python, NLTK, and spaCy**.

Feel free to explore the practicals and experiment with different text inputs to understand how NLP techniques work.

---

⭐ **If you find this repository useful, consider giving it a star!**
