# Experiments

Implementing complicated ML/AI topics from scratch — the goal is deep understanding, not production code. Each notebook picks one hard concept and works through it hands-on until it clicks.

## Notebooks

| Notebook | Topic | Key Technique |
|----------|-------|---------------|
| [Simple Neural Network](Simple%20Neural%20Network.ipynb) | Image generation | Diffusion model (PyTorch) |
| [Recurrent Neural Networks](Recurrent%20Neural%20Networks.ipynb) | Time series forecasting | LSTM on US electricity data |
| [AgentIteration](AgentIteration.ipynb) | LLM interaction & code generation | Claude via claudette |
| [Obvious](Obvious.ipynb) | Movie recommendations | Collaborative filtering, matrix factorization |
| [StyleTransfer](StyleTransfer.ipynb) | Artistic style transfer | CNN feature extraction (M.F. Husain → portrait) |
| [Prior](Prior.ipynb) | Object detection anchor boxes | K-means clustering on bounding boxes |
| [Scrapingprices](Scrapingprices.ipynb) | Price extraction from e-commerce | LLM-based HTML parsing (Qwen2-7B) |
| [ImageSearchWithImages](ImageSearchWithImages.ipynb) | Content-based image retrieval | Vision Transformer + cosine similarity |
| [PositionalEmbedding](PositionalEmbedding.ipynb) | Positional encodings in transformers | Embedding visualization |

## Tech Stack

PyTorch · torchvision · Hugging Face Transformers · claudette · scikit-learn · NumPy · Matplotlib · Pandas

## Getting Started

```bash
pip install torch torchvision transformers claudette scikit-learn numpy matplotlib pandas jupyter
jupyter notebook
```

> **Note:** `Scrapingprices.ipynb` requires a GPU (A100 recommended) to run the Qwen2-7B-Instruct model locally.

## Philosophy

The best way to understand a concept is to implement it. Each notebook here tackles something that looked complex on paper — diffusion models, LSTMs, transformers, collaborative filtering — and works through it until the mechanics are clear. The code is intentionally minimal: no frameworks hiding the details.
