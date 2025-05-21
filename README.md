# 🧠 Clustering Textual Notes with Sentence Transformers & KMeans

## 📌 Overview

This project organizes short text notes into meaningful groups based on their semantic content using modern **Natural Language Processing (NLP)** and **unsupervised machine learning** techniques. By converting each sentence into a numerical *meaning vector* and clustering similar ones together, it enables topic discovery, summarization, and auto-labeling of text data.

---

## ⚙️ How It Works

1. 📦 **Libraries are loaded**  
   Uses popular Python libraries such as `sentence-transformers`, `scikit-learn`, `numpy`, and `pandas`.

2. 📝 **Text notes are defined**  
   Example: *“Artificial intelligence mimics human behavior.”*

3. 🔍 **Sentences are converted into vectors**  
   Sentences are embedded using a pretrained model like `all-MiniLM-L6-v2`.

4. 🧩 **Clustering with KMeans**  
   The sentence vectors are grouped into clusters based on semantic similarity.

5. 🧠 **Results are displayed**  
   Each note is shown under its respective group. A sample sentence is suggested as the group title.

---

## 🚀 Key Features

- ✅ Lightweight yet powerful sentence transformer model (`all-MiniLM-L6-v2`)
- ✅ Requires **no training data** – fully unsupervised
- ✅ Auto-generates group titles from sentence context
- ✅ Highly readable and modular Python code
- ✅ Easily extendable to larger datasets

---

## 🛠️ Technologies Used

| Technology              | Purpose                             |
|--------------------------|-------------------------------------|
| 🐍 Python               | General programming language        |
| 🤖 Sentence Transformers| Sentence embeddings                 |
| 📊 scikit-learn         | KMeans clustering                   |
| 🔢 NumPy                | Numerical operations                |
| 🧾 Pandas               | Data structuring & analysis         |

---

## 📚 Use Cases

- 🏫 Categorizing educational content by topic  
- 💬 Grouping customer feedback for sentiment analysis  
- 📰 Automatically clustering news headlines  
- 📂 Organizing research notes into themes  

---

## 💡 Why It Matters

This project goes beyond grouping — it helps **understand** what each group is about by suggesting a representative sentence as a potential title. This adds context and meaning to otherwise unstructured data.

---

## 📄 License

This project is open-source and free to use for personal, academic, or non-commercial purposes.
