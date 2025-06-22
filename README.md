# VoiceCheck-AI

VoiceCheck-AI is a lightweight AI-powered system designed to distinguish between real and fake (synthetically generated) human speech. It leverages a mini version of the LibriSpeech dataset for real samples and generates fake samples using neural text-to-speech (TTS) models.

---

## Project Goals

- ✅ Build a minimal, reproducible dataset of real vs. fake voice samples
- ✅ Visualize waveforms and spectrograms for both classes
- ✅ Train a simple deep learning model for real/fake classification
- ✅ Provide explainability using visual/audio comparisons

---

## 📁 Folder Structure

```bash
VoiceCheck-AI/
├── data/                # Audio samples (real & fake)
│   └── spoof-mini/
├── models/              # Saved model files
├── notebooks/           # Jupyter/Colab notebooks
├── scripts/             # Python scripts for training/evaluation
├── utils/               # Utility/helper functions
├── LICENSE
└── README.md
```

---
