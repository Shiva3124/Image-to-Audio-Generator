# 🎙️ Shivaram Gen AI – Text to Speech Converter

A simple **Text-to-Speech (TTS)** application powered by the **Google Text-to-Speech (`gTTS`)** library.  
This script takes any text input from the user and generates an **audio file (MP3)** that speaks the entered text.

---

## 🚀 Features
- Converts text input into natural-sounding speech  
- Generates an `output_audio.mp3` file automatically  
- Lightweight and easy to run in **Google Colab** or **Python**  
- Uses **gTTS (Google Text-to-Speech)**  

---

## 🧠 How It Works
1. The script prompts you to enter a line of text.  
2. It uses the `gTTS` library to synthesize speech from the input text.  
3. The generated audio is saved as `output_audio.mp3`.  
4. The audio is automatically played (if supported by your environment).  

---

## 🧩 Requirements
Before running the script, make sure you have:
- Python 3.7 or above  
- `gtts` library installed  

You can install dependencies with:
```bash
pip install gtts
```

---

## ▶️ Usage

### Option 1: Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/shivaram-gen-ai.git
   cd shivaram-gen-ai
   ```
2. Run the script:
   ```bash
   python shivaram_gen_ai.py
   ```
3. Enter your desired text and enjoy your generated speech!

### Option 2: Run in Google Colab
1. Open a new Colab notebook.  
2. Upload `shivaram_gen_ai.py`.  
3. Run all cells to generate speech.

---

## 📁 Output
The generated file:
```
output_audio.mp3
```

---

## 💡 Example
**Input:**
```
Hello, welcome to Shivaram Gen AI!
```

**Output:**
🎧 Plays “Hello, welcome to Shivaram Gen AI!”  
and saves it as `output_audio.mp3`.

---

## 🛠️ Technologies Used
- **Python 3**
- **Google Text-to-Speech (gTTS)**
- **IPython.display** (for Colab playback)

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
