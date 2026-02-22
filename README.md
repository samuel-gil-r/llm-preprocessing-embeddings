# LLM Text Preprocessing and Embeddings - Chapter 2

This notebook follows Chapter 2 of "Build a Large Language Model From Scratch" 
by Sebastian Raschka. It covers how raw text is transformed into numerical 
representations that language models can understand.

---

## What this notebook covers

- Loading and tokenizing raw text
- Building a vocabulary from scratch
- Handling unknown tokens with special tokens
- Creating a sliding window DataLoader for training
- Generating token and positional embeddings

---

## How to run it

**1. Clone the repository:**
```bash
git clone https://linkrepositorio
cd llm-preprocessing-embeddings
```

**2. Install dependencies:**
```bash
pip install torch tiktoken
```

**3. Make sure `the-verdict.txt` is in the same folder as the notebook.**

**4. Open the notebook and run all cells:**
```bash
jupyter notebook embeddings.ipynb
```

---

## Results summary

| Step | Result |
|------|--------|
| Text length | 20,479 characters |
| Total tokens | 4,649 |
| Vocabulary size | 1,161 (including special tokens) |
| Token embeddings shape | [2, 8, 256] |

---

## References

- [Build a Large Language Model From Scratch - Sebastian Raschka](https://github.com/rasbt/LLMs-from-scratch)
- [Chapter 2 notebook](https://raw.githubusercontent.com/rasbt/LLMs-from-scratch/main/ch02/01_main-chapter-code/ch02.ipynb)

---

## Author
- Samuel Antonio Gil Romero

## Course
- TDSE Transformacion Digital y Soluciones Empresariales
