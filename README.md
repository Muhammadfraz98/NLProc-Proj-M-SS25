# Sentence Embedding and Semantic Search with FAISS

This project explores how to represent sentences as vectors using `sentence-transformers` and how to perform fast similarity search using **FAISS**.

We:
- Encode sentences using the `all-MiniLM-L6-v2` model.
- Compare sentence similarity with cosine similarity.
- Visualize the embeddings using PCA and t-SNE.
- Use FAISS to efficiently search for the most similar text chunks in a dataset.

---

## 🔧 Setup

1. Install requirements:
   ```bash
   pip install sentence-transformers faiss-cpu matplotlib scikit-learn


2. Launch Jupyter Notebook by writing in bash:
		jupyter notebook

3. Run the cells one by one (Shift + Enter) in notebook on cells
