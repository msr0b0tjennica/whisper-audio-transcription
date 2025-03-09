# 🎧 Whisper Audio Transcription

This project transcribes **MP3 audio files** into text using **OpenAI's Whisper model** in **Google Colab**. No need to install Whisper on your local machine—just upload your file, run the notebook, and get a transcription!

## 🚀 Features
✅ Supports MP3 files  
✅ Automatic speech-to-text conversion  
✅ Saves transcription as a `.txt` file  
✅ Works with different Whisper model sizes  

---

## 📂 **How to Set Up the Project on GitHub (Without Cloning)**
### **Step 1: Create a GitHub Repository**
1. **Go to [GitHub](https://github.com/)** and **log in**.
2. **Click the "+" icon** (top-right corner).
3. Select **"New repository"**.
4. **Enter the repository details**:
   - **Repository name:** `whisper-audio-transcription`
   - **Description:** `Automatically transcribe MP3 audio files using OpenAI's Whisper model in Google Colab.`
   - **Visibility:** Choose **Public** or **Private**.
5. **Click "Create repository"** (big green button at the bottom).

---

### **Step 2: Upload the Files to GitHub**
1. **Go to your newly created repository**.
2. **Click "Add file" (dropdown) → Select "Upload files"**.
3. **Drag and drop** the following files or click **"choose your files"** to upload manually:
   - `transcribe.ipynb` (Google Colab notebook).
   - `README.md` (this file).
   - `requirements.txt` (dependency list).
4. **Scroll down to "Commit changes"**, add a message (e.g., `"Initial upload"`), and click **"Commit changes"**.

---

### **Step 3: Run the Code in Google Colab**
1. Open [Google Colab](https://colab.research.google.com/).
2. Click **"File" → "Upload Notebook"** (top-left).
3. Select `transcribe.ipynb` from your local machine.
4. Run the code to upload an MP3 file and transcribe the audio.

---

## 🛠️ **Installation (If Running Locally)**
If you prefer running this locally, install the dependencies:
```sh
pip install -r requirements.txt
sudo apt update && sudo apt install ffmpeg
```

---

## 📚 **Usage**
1. **Upload an MP3 file** in Google Colab.
2. **Run the notebook** to transcribe the audio.
3. **Download the generated `.txt` file** with the transcription.

---

## 🐝 **License**
This project is licensed under the **MIT License**.

