# 🎙️ Hindi Audio-to-Text NLP Pipeline

A complete workflow for converting Hindi speech to text, detecting language, and performing NLP tasks such as POS tagging and NER — all using Google Colab.

## 🚀 Project Overview

This project demonstrates a complete NLP pipeline built in Google Colab, starting from Hindi audio (MP3) and ending with linguistic analysis using Stanza.

- ✔️ Features

- 🎧 Convert MP3 audio to WAV using pydub

- 🗣️ Speech-to-Text using SpeechRecognition with Google API

- 🌐 Language Identification using langdetect

- 🧠 Linguistic Processing with Stanza

  - Tokenization

  - POS Tagging

  - Named Entity Recognition (NER)
 
## 📦 Libraries Used

| Library            | Purpose                                   |
|--------------------|-------------------------------------------|
| SpeechRecognition  | Converts WAV audio to text                |
| pydub              | Converts MP3 → WAV                        |
| langdetect         | Detects the language of the extracted text|
| stanza             | NLP tasks – POS, NER, tokenization        |
