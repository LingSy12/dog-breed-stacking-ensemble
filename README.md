# Dog Breed Classification — Stacking Ensemble Experiment

An experiment notebook from the dog‑breed recognition work that builds a **stacking
ensemble**: predictions from several CNN backbones (e.g. Inception / ResNet family
models) are combined by a meta‑learner to improve overall classification accuracy
beyond any single model.

## 📓 Contents

- `Ensumble_Stacking.ipynb` — loads the base CNN models, gathers their predictions,
  and trains a stacked meta‑classifier on top of them.

## ▶️ How to run

1. Open the notebook in Jupyter, Google Colab or Kaggle.
2. Provide the trained base models / their predictions and your dog‑breed dataset.
3. Run the cells to train the stacking meta‑learner and evaluate the ensemble.

## 🔗 Related projects

- [Dog Breed Recognition using Deep Learning](https://github.com/LingSy12/Dog-Breed-Recognition-using-Deep-Learning) — base CNN benchmarking (FYP)
- [Enhancing Dog Breed Classification with Feature Fusion of Pre‑trained CNNs](https://github.com/LingSy12/Enhancing-Dog-Breed-Classification-with-Feature-Fusion-of-Pre-trained-CNNs-and-Machine-Learning) — feature‑fusion follow‑up (MSc)
