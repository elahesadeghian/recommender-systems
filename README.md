# Recommender Systems (MovieLens)

Hands-on notebooks for building recommender systems on the **MovieLens (small)** dataset.

## Notebooks
- `notebooks/01_movielens_item_item_knn.ipynb` — Item–item KNN (cosine). Includes a quick baseline **Precision@10**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
  https://colab.research.google.com/github/elahesadeghian/recommender-systems/blob/main/notebooks/01_movielens_item_item_knn.ipynb)

## Example
Top-10 similar movies for *Toy Story (1995)* using item–item cosine similarity.

## Results (baseline)
- Precision@10 (80/20 random split): **0.095**  

## Roadmap
- [x] Item–item KNN + Precision@10
- [ ] SVD (Surprise) + RMSE (5-fold), comparison table
- [ ] Streamlit demo (live)
- [ ] Content-based / Hybrid

## Tech
`Python`, `pandas`, `numpy`, `scikit-learn`
