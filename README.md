# 🎧 AI Audio Stem Splitter (Google Colab)

An advanced AI-powered stem splitter and vocal remover utilizing SOTA architectures (**BS-RoFormer**, **Mel-RoFormer**, **HTDemucs**) powered by `audio-separator`.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SteFabolous/stem-splitter-with-google-colab/blob/main/stem_splitter.ipynb)

## ✨ Features
- 🎤 **Top-Tier Vocal Isolation**: Powered by **BS-RoFormer** to extract crystal-clear vocals or remove them entirely without phasing artifacts or frequency loss.
- 🎛️ **Multi-Stem Separation**: Built-in support for **HTDemucs v4** to split tracks into 4 distinct stems (*Vocals, Drums, Bass, Other*).
- 🔗 **Flexible Inputs**: Load audio files directly from Google Drive or download audio on the fly via YouTube URLs.
- 📁 **High-Quality Export**: Saves studio-grade WAV files directly to your Google Drive folder.

## 🚀 Quick Start
1. Click the **Open in Colab** badge above.
2. Ensure your hardware accelerator is set to **GPU** (`Runtime` -> `Change runtime type` -> `T4 GPU`).
3. Run **Step 1** to mount Google Drive and install dependencies.
4. Customize your settings in **Step 2** and start splitting!

## 🤖 Model Breakdown
- **BS-RoFormer (ViperX)**: The absolute SOTA for vocal removal and isolation. Minimum bleed, max clarity.
- **Mel-RoFormer (Kim)**: Exceptional performance on high-pitched vocals and complex high-frequency audio.
- **HTDemucs v4**: Best option when you need full 4-stem instrumentation.
