# 🧠 Sequence Models: Zero to Hero
### RNN → LSTM → GRU → WaveNet | CMPE 258 Deep Learning | Spring 2026

---

## 📹 Video Walkthrough

[![Watch the Video](https://img.shields.io/badge/YouTube-Watch%20Walkthrough-red?style=for-the-badge&logo=youtube)](YOUR_YOUTUBE_LINK_HERE)

> 🔗 **Video Link:** [YOUR_YOUTUBE_LINK_HERE](YOUR_YOUTUBE_LINK_HERE)
> *Full code walkthrough — block by block explanation with outputs*

---

## 📓 Colab Notebook

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

> 🔗 **Colab Link:** [YOUR_COLAB_LINK_HERE](YOUR_COLAB_LINK_HERE)
> *Executed notebook with all outputs saved*

---

## 📖 What This Notebook Covers

This notebook is a complete, from-scratch introduction to **sequence modeling** using PyTorch. All four architectures are trained on the same character-level language modeling task — predicting the next character in a text — so results are directly comparable.

| Section | Topic |
|---------|-------|
| Part 1 | The World of Sequences — why order matters, data pipeline |
| Part 2 | Vanilla RNN — hidden state, backprop through time, vanishing gradients |
| Part 3 | LSTM — cell state, forget/input/output gates, long-range memory |
| Part 4 | GRU — simplified gating, faster training, comparable performance |
| Part 5 | Deep RNNs & Practical Tricks — stacking, dropout, bidirectional, gradient clipping |
| Part 6 | WaveNet — causal & dilated convolutions, parallelism advantage |
| Part 7 | Grand Comparison — benchmarks, loss curves, generated text, when to use what |

---

## 🛠️ Tech Stack

- **Framework:** PyTorch 2.x
- **Task:** Character-level language modeling
- **Hardware:** Google Colab (GPU recommended)
- **Inspired by:** Aurélien Géron's *Hands-On ML with Scikit-Learn, Keras, and TensorFlow*

---

## 🚀 How to Run

1. Open the Colab link above
2. Go to `Runtime → Change runtime type → GPU`
3. Run all cells top to bottom (`Runtime → Run all`)

---

## 📊 Key Takeaways

| Model | Parameters | Best Use Case |
|-------|-----------|---------------|
| RNN | Fewest | Simple sequences, quick baselines |
| LSTM | Most | Long-range dependencies, classic NLP |
| GRU | Medium | Faster LSTM alternative, often equally good |
| WaveNet | Medium | Audio generation, fast parallel training |

---

*CMPE 258 — Deep Learning | San Jose State University | Spring 2026*
