# Image and Text Generators

This repository contains two Jupyter Notebooks that demonstrate the implementation of:

1. **Image to Text Generator**: A tool to extract text from images.
2. **Text to Image Generator**: A tool to create images based on textual descriptions.

## Features

### Image to Text Generator
- Extracts text from images using Optical Character Recognition (OCR).
- Handles multiple image formats (e.g., PNG, JPEG).
- Outputs extracted text in a structured format.

### Text to Image Generator
- Generates images based on textual prompts.
- Utilizes generative models to create realistic or artistic visuals.

## Requirements

To run these notebooks, ensure you have the following installed:

- Python 3.8 or higher
- Jupyter Notebook
- Required libraries (specified in `requirements.txt`):
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `opencv-python`
  - `pytesseract` (for OCR functionality)
  - `Pillow`
  - Generative AI tools (e.g., `stable-diffusion`, `DALL-E`, or `GANs`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ImageTextGenerators.git
   ```

2. Navigate to the repository directory:
   ```bash
   cd ImageTextGenerators
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. (Optional) Ensure `pytesseract` is properly set up by downloading the Tesseract-OCR executable and adding it to your system path. Refer to the [Tesseract installation guide](https://github.com/tesseract-ocr/tesseract).

## Usage

### Running the Notebooks

#### Image to Text Generator
1. Open the `ImageToTextGenerator.ipynb` file in Jupyter Notebook:
   ```bash
   jupyter notebook ImageToTextGenerator.ipynb
   ```

2. Follow the instructions in the notebook to upload an image and extract text.

#### Text to Image Generator
1. Open the `TextToImageGenerator.ipynb` file in Jupyter Notebook:
   ```bash
   jupyter notebook TextToImageGenerator.ipynb
   ```

2. Provide a text prompt to generate an image.

## Technologies Used

- **Image Processing**: OpenCV, Pillow
- **OCR**: Tesseract OCR
- **Generative Models**: Stable Diffusion / DALL-E / GANs (depending on implementation)
- **Visualization**: Matplotlib

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

## Author(s)

- Your Name - Sonal

## Acknowledgments

- Inspired by advancements in AI and computer vision.
- Tutorials and documentation from OpenCV, PyTorch, and Tesseract communities.

