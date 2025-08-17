# granny-gpt
Granny GPT – A fun AI grandma that talks, slides into view when speaking, and can guess images. Includes drag &amp; drop image recognition, TTS, and a bit of silly personality. Inspired by Failboat.




# GrannyGPT

GrannyGPT is a fun, experimental Python project where "Granny" can talk, answer questions, and even guess objects/images you show her.  
She can be used for streams, recordings, or just for fun.

---

## ✨ Features
- **Talking Granny** — She speaks out whatever you type or say.
- **Voice Input** — Talk to her with your microphone.  
- **Text Input** — No mic? Type instead.
- **Sliding Animation** — Granny slides into frame when talking and slides out when quiet.
- **Custom Images** — Drag & drop or replace `granny.png` to give her a new look.  
- **Smarter Over Time** — She "learns" new guesses when you teach her.  
- **Fun References** — Includes silly objects, characters, and even absurd guesses like "cow on a skateboard".  
- **Chroma Key Ready** — Background is solid for OBS streaming.

---

## 📦 Installation

### 1. Install Python
- [Download Python 3.11](https://www.python.org/downloads/release/python-3116/)  
  (Make sure to check **"Add to PATH"** during installation)

### 2. Install Dependencies
Open **CMD** in the project folder and run:

```sh
pip install TTS
pip install SpeechRecognition
pip install pyaudio
pip install pillow

⚠️ If pyaudio fails to install on Windows:

Go here: [Unofficial PyAudio builds](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)

Download the version for Python 3.11 x64

Install with:

pip install PyAudio-0.2.11-cp311-cp311-win_amd64.whl

▶️ Running Granny

Start Granny with:

python main.py


On first launch, enter your name.

Granny will greet you and start in "off-screen" mode.

When she speaks, she will slide into frame.

When silent, she slides back out.

🎨 Customization

(this is only if you want to) Replace granny.png with your own PNG (keep it around 539x420 px for best fit).

Drag & drop a PNG into her window to make her hold it.

📜 Credits

Project Author: Luka

Inspired by fun experiments with TTS and object recognition.

Thanks to open-source libraries like TTS, SpeechRecognition, and Pillow.

🐛 Bugs & Feedback

If you find a bug, please report it to:
📧 your-email@example.com

📺 Streaming

Use OBS with a Chroma Key filter to remove the background and put Granny into your streams.
