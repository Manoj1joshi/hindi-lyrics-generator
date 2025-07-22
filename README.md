# hindi-lyrics-generator
Character-level LSTM model to generate Hindi song lyrics using Pytorch
# 🎵 Hindi Lyrics Generator using LSTM

This project implements a character-level LSTM model using PyTorch to generate Hindi song lyrics. It is trained on a Hinglish-Hindi parallel corpus and outputs poetic, Bollywood-style lyrics. The generated lyrics can also be converted into audio using Google's Text-to-Speech API (`gTTS`).

## 🔗 Open in Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Manoj1joshi/hindi-lyrics-generator/blob/main/hindi_lyrics_generator.ipynb)

## 🛠 Features

- Character-level text generation using LSTM
- Trained on Hindi lyrics with PyTorch
- Custom dataset class using `torch.utils.data.Dataset`
- Realistic output with low loss (~0.08)
- Text-to-speech with `gTTS` to generate `.mp3` of lyrics

## 📊 Sample Output

चांदनी में मारूँ तो छोरी पट जाए
छोरी पट जाए भंकस दिल में तेरे क्या है मुझको बता दे
तेरे मेरे बीच का ये पर्दा हटा दे
...


## 📦 Dependencies

- `torch`
- `numpy`
- `gtts`
- `google.colab`
- `kaggle` (for dataset download)

## 📂 Dataset

Kaggle: [Hinglish-Hindi Parallel Corpus](https://www.kaggle.com/datasets/stutig29/hinglish-hindi-parallel-corpus)

## 📄 License

Apache 2.0
