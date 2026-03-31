# Audify
Audify is an AI-powered tool that simplifies audio editing by allowing users to edit speech through text. Instead of manually re-recording or trimming audio, users can modify the transcript, and the system automatically updates the audio accordingly.  This project focuses especially on supporting Egyptian Arabic
Problem

Recording audio (lectures, podcasts, etc.) often includes:

Mistakes that require re-recording
Time-consuming manual editing
Lack of support for Egyptian Arabic in current tools
🎯 Objective
Save time by enabling fast audio editing using text
Reduce cost by minimizing need for professional editors
Support Egyptian Arabic speech processing
⚙️ Techniques & Methodology
1. Speech-to-Text (STT)
Converts audio into text
Used to generate editable transcripts
2. Text-to-Speech (TTS)
Converts edited text back into audio
Maintains natural voice output
3. Voice Cloning
Preserves speaker identity and tone
Ensures edited audio sounds consistent
4. Audio Processing Pipeline
Audio → Speech Recognition → Editable Text
Edited Text → Speech Synthesis → Final Audio
🧠 Technologies Used
Deep Learning models for STT & TTS
Transformer-based models (e.g., GPT-like components)
Vocoders (e.g., HiFi-GAN)
Hugging Face ecosystem
📊 Dataset
Custom dataset of Egyptian Arabic speech
Includes diverse recordings and transcriptions
Covers various tones, words, and speaking styles
📈 Results
Speech-to-Text:
WER: 35%
CER: 12%
Demonstrated successful audio editing via text
🚀 Future Work
Improve Egyptian dialect accuracy
Train on larger datasets (e.g., YouTube audio)
Integrate with social media platforms
Extend to video editing
