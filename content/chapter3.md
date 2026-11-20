---
title: "Choosing a Whisper model"
nav_order: 4
---

# Choosing a Whisper model

One of the most important decisions when using Whisper is selecting an appropriate model size. Whisper is available in several models: Tiny, Base, Small, Medium, Large-v2, and Large-v3. Some implementations also provide Turbo, a speed-optimized variant of the large-model family. These models differ in their computational requirements, processing speed, transcription quality, and the way they represent spoken language.  

Model selection affects more than transcription accuracy alone. Different Whisper models can produce noticeably different transcripts from the same recording. Smaller models are generally more prone to recognition errors, while larger models tend to generate cleaner and more readable transcripts. However, larger models often achieve this by omitting repetitions, hesitations, filler words, and other characteristics of spontaneous speech. As a result, the most accurate transcript is not always the most suitable transcript for a particular purpose.  

For example, a model that produces excellent captions or meeting minutes may not be the best choice for linguistic research, where preserving spoken-language phenomena can be more important than maximizing readability. Similarly, a model that produces the highest transcription quality may require substantially more computational resources than a smaller alternative 