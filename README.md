# Automatic-Music-Generator

# 🎵 Automatic Music Generator

This project uses **LSTM (Long Short-Term Memory networks)** to generate piano music automatically. The model learns patterns from classical piano MIDI files and creates new sequences.

---

## 🚀 How It Works

1. **Preprocess Data** — Extract notes & chords from MIDI files.
2. **Train LSTM Model** — Learn musical patterns and long-term dependencies.
3. **Generate Music** — Predict new notes and create a MIDI file.

---

## 🧠 Tech Stack

* Python, TensorFlow / Keras
* NumPy, Music21 (MIDI processing)

---

## 📂 Dataset

Classical piano MIDI files from various composers.
Download from [Classical Music MIDI Dataset](https://www.midiworld.com/classical.htm) and place in `dataset/`.

---

## ▶️ Run

```bash
git clone https://github.com/Nikita-V222/Automatic-Music-Generator.git
cd Automatic-Music-Generator
pip install -r requirements.txt
python train.py
python generate.py
```

Generated music will be saved as a `.midi` file.
