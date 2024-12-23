# Text-to-Image-Generator
This project demonstrates how to generate images from textual prompts using a pre-trained diffusion model. It leverages the Dreamlike Diffusion model and integrates functionality to customize image dimensions and count.
## Features
1. Uses the Stable Diffusion pipeline for text-to-image generation.
2. Allows user input for:
- Text prompt.
- Number of images to generate (up to 3).
- Image width and height (adjusted to be divisible by 8 automatically).
3. Displays the generated images using Matplotlib.
## Prerequisites
1. Python 3.7 or higher
2. CUDA-compatible GPU (for optimal performance)
## Installation
Clone the repository or download the script.
Install the required Python packages: "pip install diffusers transformers accelerate matplotlib"
## Usage
Run the script in your Python environment: "python text_to_image_generator.py"
