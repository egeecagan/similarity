# Similarity

Documents and stock returns are both treated as vectors. Similarity is the
angle between them.

## What's inside

**Part A: Text search**
- Turn filings into vectors with TF-IDF, computed by hand
- Score every document against a query with one matrix-vector product, `Aq`
- Rank with cosine similarity and show why normalization matters

**Part B: Stock returns**
- Show that cosine similarity of mean-centered returns is the correlation
- Check the Cauchy-Schwarz and triangle inequalities on real data
- Write a portfolio's return as a linear combination of stock returns, `Ax`

## Status

- [x] Toy example: count matrix, dot product, cosine similarity
- [ ] TF-IDF
- [ ] Search on SEC EDGAR filings
- [ ] Stock returns and correlation
- [ ] Portfolio as a linear combination
