# Learning Transformers: nanoGPT Exploration

## Overview

This repository documents my learning journey through Andrej Karpathy's tutorial on building a GPT model from scratch, using nanoGPT as a reference. Due to compute limitations, I experimented with training on Google Colab.

## Resources

### Video and Articles:

- [YouTube Video: "Build GPT – From Scratch, Spelled Out"](https://youtu.be/kCc8FmEb1nY?si=YXVM6ze6Aaua0dC4)
- [Medium Article: "Train Your Own Language Model with nanoGPT"](https://sophiamyang.medium.com/train-your-own-language-model-with-nanogpt-83d86f26705e)

### Code and Research Papers:

- [Google Colab Notebook](https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-?usp=sharing)
- [nanoGPT Repository](https://github.com/karpathy/nanoGPT)
- ["Attention is All You Need" Paper](https://arxiv.org/abs/1706.03762)

## Learning Highlights

- **Transformer Architecture:** The model is built following the principles of the "Attention is All You Need" paper.
- **Self-Attention Mechanism:** Understanding the role of attention heads and positional encoding.
- **TinyShakespeare Dataset:** Used as a small-scale dataset for training the transformer.
- **Training on Google Colab:** Limited compute power required adjustments to batch sizes and training iterations.

## Running nanoGPT on Colab

1. Clone the nanoGPT repository:
   ```sh
   git clone https://github.com/karpathy/nanoGPT.git
   cd nanoGPT
   ```
2. Install dependencies:
   ```sh
   pip install torch numpy transformers
   ```
3. Run training (adjust batch size for limited compute):
   ```sh
   python train.py --dataset=tinyshakespeare --batch_size=2
   ```

## Next Steps

- Experimenting with different datasets.
- Fine-tuning on custom text corpora.
- Exploring optimizations for running on limited hardware.

---

This repository serves as a documentation of my progress and learnings in understanding GPT and transformers. Contributions, suggestions, and discussions are welcome!
