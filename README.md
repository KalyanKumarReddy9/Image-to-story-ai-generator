# Image to Story Generator

## Overview
The **Image to Story Generator** is an AI-powered web application that generates creative, personalized, and kid-friendly stories based on images. This solution leverages **Computer Vision** and **Natural Language Processing (NLP)** techniques to convert images into engaging narratives for children. It also supports multilingual text-to-speech conversion for an interactive storytelling experience.

## Features
- **Image-based Story Generation**: Upload an image, and the system will generate a creative story incorporating elements from the image.
- **Multilingual Support**: Translate the generated story into various languages (e.g., English, Spanish, French, etc.).
- **Text-to-Speech**: Convert the generated text into speech and listen to the story.
- **Age-appropriate Language**: The generated stories are tailored for kids aged 5-12.

## Technologies Used
- **Computer Vision**: BLIP (Bootstrapping Language-Image Pretraining) for generating image captions.
- **Natural Language Processing (NLP)**: GPT-2 for generating creative stories based on captions.
- **Text-to-Speech**: Google Text-to-Speech (gTTS) for audio output.
- **Web Framework**: Streamlit for creating an interactive web interface.
- **Translation**: Google Translator API for multilingual story generation.

## Requirements

### Prerequisites
- Python 3.x
- Git
- Pip (Python package manager)

### Dependencies
Before running the application, make sure to install the required dependencies by running the following command:

```bash
pip install -r requirements.txt
