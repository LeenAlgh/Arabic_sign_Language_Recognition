# Arabic Sign Language Words Recognition 🤟🗣️

This project implements a deep learning-based system to recognize **Arabic Sign Language words** in real-time. It uses sequential models (LSTM and GRU) to classify 10 common Arabic sign language words from webcam-captured sequences.

---

## 🧠 Project Overview

This system translates a set of commonly used **Arabic Sign Language words** into text using time-series models. The gestures were captured in real time and saved in `.npy` format, enabling accurate temporal feature extraction.

---

## 🗣️ Recognized Words (الكلمات المعترف بها)

| English Word        | Arabic Translation     |
|---------------------|-------------------------|
| yes                 | نعم                     |
| assalamu_alaikum    | السلام عليكم            |
| how_are_you         | كيف حالك؟               |
| alhamdulelah        | الحمد لله               |
| an_sha_allah        | إن شاء الله             |
| please              | من فضلك                 |
| welcome             | أهلاً وسهلاً            |
| thanks              | شكراً                   |
| congrats            | مبروك                   |
| happy               | سعيد                    |

---

## 🧪 Models Used

Both of the following sequential models were trained and evaluated:
- **LSTM (Long Short-Term Memory)**
- **GRU (Gated Recurrent Unit)**

---

## 📂 Dataset

-  10 word classes
-  Real-time collected gesture sequences
-  Each word stored in a folder with 30 subfolders (each subfolder = one sample)
-  Saved in `.npy` format for efficient training

