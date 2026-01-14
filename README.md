# Piper TTS pipeline

This repository contains a complete pipeline for training, preprocessing, and exporting a custom Text-to-Speech (TTS) model. It covers data preparation, model training, and ONNX export for deployment purposes.

## 📁 Project Structure

| File | Description |
|------|-------------|
| `TTS_dataset_preprocess.ipynb` | Preprocesses the audio and text data into a format suitable for training |
| `TTS_custom_training.ipynb` | Trains the TTS model using a specified configuration and dataset |
| `TTS_export.ipynb` | Exports the trained model to ONNX format for inference or deployment |

---

## 🚀 Features

- Preprocessing of raw datasets into JSONL format
- Configuration-driven model training using PyTorch
- ONNX export for runtime-efficient deployment
- Modular and customizable pipeline

---

## 🛠️ Requirements

Make sure to install the Python dependencies especially all dependencies in the depend.py.

## Models Location

You can find out the models at https://huggingface.co/rhasspy/piper-voices or https://github.com/rhasspy/piper/blob/master/VOICES.md.
