# Plague Dr Mastering Suite

---

### Special Thanks

This project is made possible by the vision, guidance, and support of my brother, **Russ S**. His contributions and encouragement are the foundation of this work. Much love, Brother.

---

## Project Overview

The **Plague Dr Mastering Suite** is an AI-powered audio toolkit designed for musicians, producers, and creators. Wrapped in a unique steampunk theme, this suite provides a powerful, all-in-one solution for audio processing, from stem separation to final mastering and analysis, all running within a user-friendly notebook environment.

## Key Features

This suite combines several powerful tools into a single, cohesive pipeline:

* **🎛️ 4-Stem Separation:** Upload any track and automatically separate it into high-quality vocal, drum, bass, and other instrument stems using Meta's Demucs model.
* **🎤 AI-Powered Transcription:** Automatically generate lyrics from the separated vocal stem using OpenAI's Whisper model.
* **🔊 Multi-Preset Mastering:** Choose from several distinct mastering presets to finalize your track's sound:
    * **Aggressive & Loud:** For a modern, punchy, and competitive sound.
    * **Clean & Bright:** A more subtle master that adds clarity and "air."
    * **Warm & Vintage:** Simulates an analog-style master with warmth and smooth high-end.
* **📊 In-Depth Track Analysis:** A professional analysis and comparison tool that provides critical feedback on your audio, including:
    * Side-by-side A/B players for the original vs. mastered track.
    * Comparative stats for Loudness (LUFS), Peak Level, Dynamic Range, and Tempo (BPM).
* **☁️ Google Drive Integration:** All processed files, including stems and final masters, are automatically saved to your personal Google Drive.

## How to Use

This project is currently implemented as a Google Colab notebook.

1.  **Open in Colab:** Click the "Open in Colab" badge at the top of this README.
2.  **Set the Runtime:** For the best performance, ensure your runtime is set to use a **GPU**. Go to **Runtime > Change runtime type > GPU**.
3.  **Run the Code:** Execute the single code cell in the notebook.
4.  **Connect to Google Drive:** The first time you run the app, you will be prompted to connect and authorize your Google Drive account. This is where your files will be saved.
5.  **Use the Interface:** Once the Gradio UI launches, you can begin uploading and processing your audio tracks.

## Future Development

This Colab notebook is the first step in a larger vision. As outlined in the project blueprint, future development plans include:
* A native **Android Application** on the Google Play Store.
* A premium tier with advanced features hosted on a robust **Microsoft Azure backend**.
* A full **Web Application** version for browser-based access.
* Deeper platform integrations, including direct import/export with **SoundCloud**.

