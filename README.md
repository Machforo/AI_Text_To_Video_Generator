# 🧠 AI Text-to-Video Generation 🎬

This project is an **AI-powered pipeline** that transforms raw text into engaging narrated videos by automatically generating scripts, voiceovers, background visuals, and synchronized captions.

> Built for creators, educators, and developers who want to automate video creation using the power of AI.

---

## ✨ Features

- **Script Generation**: Transforms your input text into structured, narratable scripts.
- **AI Voiceover**: Converts scripts into lifelike audio using TTS models.
- **Video Sourcing**: Fetches and stitches relevant background videos from search queries.
- **Timed Captions**: Creates subtitle files aligned with the voiceover.
- **Rendering Engine**: Combines video, audio, and captions into a final MP4 video.

---

## 🧪 Example Notebook

Check out [`Text_to_Video_example.ipynb`](Text_to_Video_example.ipynb) for a hands-on demo.

This notebook shows:
- How to input raw text.
- Step-by-step pipeline execution (script ➝ audio ➝ video ➝ captions ➝ render).
- Final output: an automatically generated video file.

---

## 🗂️ Project Structure

```
TEXT-TO-VIDEO-AI-MAIN/
│
├── app.py # Main pipeline script
├── utils.py # Utility functions
├── requirements.txt # Dependencies
├── README.md # This file
├── .gitignore
│
├── utility/
│ ├── audio/
│ │ └── audio_generator.py # Text-to-Speech generation
│ └── captions/
│ └── timed_captions_generator.py # Timed caption generation
│
├── render/
│ └── render_engine.py # Final video rendering
│
├── script/
│ └── script_generator.py # Converts raw text to script
│
├── video/
│ ├── background_video_generator.py # Downloads background videos
│ └── video_search_query_generator.py # Generates search queries
```


---

## 🚀 Getting Started

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/text-to-video-ai-main.git
cd text-to-video-ai-main
```

### Step 2: Install Requirements

```bash
pip install -r requirements.txt
```
### Step 3: Run the demo code

Launch the example notebook

```bash
jupyter notebook Text_to_Video_example.ipynb
```

Or run the pipeline directly

```bash
python app.py
```

## 📁 Output

The output is a fully rendered .mp4 video file containing:

-AI voiceover narration

-Relevant background footage

-Timed captions

## Contact
For feedback, suggestions, or collaboration:

Mail : atharvkumar43@gmail.com

Linkedin : https://www.linkedin.com/in/atharv-kumar-270337222/



