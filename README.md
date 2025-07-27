# 🎙️ Voice Cloning with Open-Source Text-to-Speech (TTS) Models

This project focuses on **voice cloning and synthesis** using advanced open-source TTS models. The primary objective is to evaluate and experiment with **four Hugging Face models** on a **custom dataset** for personalized voice cloning.

---

## 📌 Task Overview

**Task 01:** Voice Cloning with Open-Source TTS Models  
**Platform:** Google Colab / Kaggle  
**Dataset:** Custom dataset (processed from LibriSpeech) with 5–10s audio clips and transcripts  
**Goal:** Evaluate inference speed, VRAM efficiency, and voice quality using fine-tuning and LoRA adaptation.

---

## 🧠 Models Used

The following Hugging Face-supported models were explored:

1. **Orpheus 3B**
2. **Kokoro-82M**
3. **CSM-1B**
4. **XTTS-v2**

Each model was tested for voice cloning performance using the same dataset.

---

## 🗂️ Dataset

- Source: Preprocessed LibriSpeech subset
- Total samples: **257 accepted audio-text pairs**
- Format: 5–10 seconds audio `.wav` with paired transcripts
- Output Directory: `/processed_data/`

---

## 📊 Evaluation Criteria

- ✅ Inference speed
- ✅ VRAM usage
- ✅ Voice naturalness and similarity (Subjective & MOS score-based)
- ✅ Compatibility with LoRA fine-tuning

---

## 🧪 Key Steps

1. **Environment Setup:** Installed required libraries and dependencies.
2. **Data Preprocessing:** Filtered and cleaned audio clips from LibriSpeech.
3. **Model Inference:** Tested all four TTS models for zero-shot and fine-tuned synthesis.
4. **Results Comparison:** Benchmarked each model's performance.

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/voice-cloning-task1.git
cd voice-cloning-task1
