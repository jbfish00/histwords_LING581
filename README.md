# Histwords — Diachronic Semantic Change in LDS Religious Language

**Course:** LING 581 | BYU
**Author:** Jacob B. Fisher

> **Fork of [williamleif/histwords](https://github.com/williamleif/histwords)** — modified to study semantic change in LDS/religious language across historical corpora.

## Modifications from Original

This fork extends the original Histwords toolkit to analyze **diachronic semantic change** in Latter-day Saint (LDS) scripture and religious language. Specifically:

- Applied the historical word embedding pipeline to religious text corpora
- Tracked semantic drift of theologically significant vocabulary over time
- Added `back_track_centroid.py`, `track_neighbor_centroid.py`, and `similarity_neighbors_tracking.py` for tracing word meaning trajectories
- Used `tsne_viz.py` for 2D visualization of embedding shifts

## Original Project

An eclectic collection of tools for analyzing historical language change using vector space semantics (SGNS word embeddings trained on Google N-grams and COHA).

**Original author:** William Hamilton (wleif@stanford.edu)
**Project website:** http://nlp.stanford.edu/projects/histwords
**Paper:** [Diachronic Word Embeddings Reveal Statistical Laws of Semantic Change (ACL 2016)](http://arxiv.org/abs/1605.09096)

## Usage

```bash
# Install dependencies
pip install -r requirements.txt

# Run example
bash example.sh
python example.py
```

## Technologies

- Python, NumPy, scikit-learn, t-SNE, SGNS word embeddings
