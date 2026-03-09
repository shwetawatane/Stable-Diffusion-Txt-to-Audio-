# Stable Diffusion Text to Audio Generator

This project is a Generative AI application that converts text prompts into audio using Stability AI's Stable Audio model.

## Project Overview
The model generates realistic audio clips based on a given text description.

Example Prompt:
"The sound of a hammer hitting a wooden surface"

The model processes the prompt and generates an audio waveform.

## Technologies Used
- Python
- PyTorch
- Hugging Face Diffusers
- Stable Audio Model
- Google Colab

## How it Works
1. Load the Stable Audio model using Hugging Face.
2. Provide a text prompt describing a sound.
3. The model generates audio based on the prompt.
4. The audio is saved as a WAV file.

## Example Output
The generated audio is saved as:

generated_audio.wav

## Future Improvements
- Build a web interface for real-time audio generation
- Allow users to download generated audio
