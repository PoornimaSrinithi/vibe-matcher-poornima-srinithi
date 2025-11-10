# Vibe Matcher — TF-IDF Prototype  
**Author:** Poornima Srinithi  
**Submission:** Mini Recommender System Assignment  

## ✅ Overview
This project implements a simple “Vibe Matcher” system using TF-IDF embeddings.  
The goal is to convert a natural-language vibe query (e.g., “energetic urban chic”)  
into a vector representation and retrieve the top-3 matching fashion products.

No paid API or OpenAI embeddings are used — the entire pipeline is local and reproducible.


## ✅ Features Implemented
- 8 fashion products with descriptions & vibe tags  
- TF-IDF vectorization of product descriptions  
- Cosine similarity based vector search  
- Fallback logic when similarity is low  
- Evaluation using precision@3 (synthetic tag relevance)  
- Latency measurement + bar chart  
- Simple click-based learn-to-rank sketch  
- Summary text file auto-generated  
- Quick runnable Python script (`vibe_matcher_quick.py`)


## ✅ Files Included
1. **Vibe_Matcher_PoornimaSrinithi.ipynb** — Full notebook with all outputs  
2. **vibe_matcher_tfidf_summary.txt** — Summary with reflections  
3. **vibe_matcher_quick.py** — Quick runnable script version


## ✅ How to Run
Open the `.ipynb` file and run all cells from top to bottom.

No API keys required.  
All dependencies are installed automatically.


## ✅ Improvements (as noted in reflection)
- Replace TF-IDF with OpenAI embeddings (text-embedding models)  
- Use Pinecone/FAISS for vector DB  
- Improve fallback tuning  
- Add real user feedback for learn-to-rank  
