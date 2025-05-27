
# 🕉️ Cartography on The Bhagavad Gita

A semantic and sentiment-driven exploration of the Bhagavad Gita using NLP techniques. This project extracts knowledge graphs, uncovers deep semantic patterns, and maps the relationships between characters and concepts using word embeddings, TF-IDF, BM25, and LSTM models—without relying on any large language models.

## 🔍 Project Objectives

- Scrape and preprocess the Bhagavad Gita verses.
- Perform semantic analysis using TF-IDF, BM25, and Word2Vec.
- Use LSTM for sentiment classification.
- Extract relationships between entities.
- Generate a cartographic knowledge graph of verses and concepts.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `TBG_1_WEBSCRAPPING.ipynb` | Web scraping Bhagavad Gita verses from online sources. |
| `TBG_2_preprocess_semantic.ipynb` | Text preprocessing including cleaning, stopword removal, and lemmatization. |
| `TBG_3_tfidf_and_bm25_semantic.ipynb` | Computes TF-IDF and BM25 similarity scores between verses. |
| `TBG_4_wrd_embed_semantic.ipynb` | Generates semantic similarity using Word2Vec vectors. |
| `TBG_5_w2v_util_semantic.ipynb` | Utility functions for word embedding handling and similarity computation. |
| `TBG_6_Relation_extraction.ipynb` | Extracts relational triples and co-occurrences among key entities. |
| `TBG_7_evaluation_metrics.ipynb` | Evaluation of semantic and sentiment-based models. |
| `Cartography_KG_on_Bhagvat_Gita_using_LSTM.ipynb` | Builds the knowledge graph and runs sentiment classification using LSTM. |
| `English.csv` | Preprocessed Bhagavad Gita verses in English. |
| `w2v.bin` | Pretrained binary Word2Vec model. |
| `bhagavad_gita_word2vec.model` | Word2Vec model trained specifically on Bhagavad Gita text. |

---

## 🧠 Methodology

### 1. Web Scraping
- Scrapes verses in English.
- Saves data to a structured `.csv` format.

### 2. Preprocessing
- Tokenization
- Lemmatization
- Stopword removal
- POS filtering

### 3. Semantic Analysis
- **TF-IDF** and **BM25**: Score verses for lexical similarity.
- **Word2Vec**: Trained on Bhagavad Gita to compute deep semantic closeness.

### 4. Relationship Extraction
- Entity co-occurrence and dependency parsing.
- Generate relationship triples for graph construction.

### 5. Sentiment Classification
- LSTM-based model to classify each verse into positive/negative/neutral sentiments.

### 6. Cartography (Knowledge Graph)
- Constructs a Knowledge Graph using extracted entities and sentiments.
- Maps key figures (e.g., Krishna, Arjuna) and themes (e.g., Dharma, Karma).

---

## 🚀 Setup Instructions

  1. Clone the repository:
   ```bash
   git clone https://github.com/Anshul-ydv/Cartography_on_The_Bhagavad_Gita.git
   cd BhagavadGita-Cartography
```

  2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

  3. Run the notebooks in order for full pipeline execution:

   * `TBG_1_WEBSCRAPPING.ipynb`
   * `TBG_2_preprocess_semantic.ipynb`
   * ... up to ...
   * `Cartography_KG_on_Bhagvat_Gita_using_LSTM.ipynb`

---

## 🛠 Requirements

Include the following in `requirements.txt`:

```txt
numpy
pandas
scikit-learn
gensim
nltk
matplotlib
seaborn
tensorflow
keras
networkx
beautifulsoup4
requests
```

---

## 📊 Sample Output

* Similarity matrices (TF-IDF, BM25, Word2Vec)
* Sentiment plot of verses over chapters
* Knowledge Graph visualization of key themes

---

## 🙏 Acknowledgements

* Bhagavad Gita translation sourced from [bhagavad-gita.org](https://www.bhagavad-gita.org).
* Inspired by semantic AI and traditional Indian scriptures.

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.


---
