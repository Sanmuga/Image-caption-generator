# Image Captioning with InceptionV3 and LSTM

This program is an implementation of an image captioning system using the InceptionV3 convolutional neural network and an LSTM (Long Short-Term Memory) neural network. Given an image, the program generates a descriptive caption for the image.

## Features

- Preprocesses images using the InceptionV3 model to extract image features.
- Utilizes an LSTM network to generate captions for images.
- Tokenizes and sequences captions.
- Trains the captioning model using image features and caption sequences.
- Generates captions for new images using the trained model.

## Prerequisites

Before running the program, make sure you have the following prerequisites installed:

- Python (>=3.6)
- Required packages: `numpy`, `PIL`, `keras`, `tensorflow`, `h5py`, `opencv-python-headless`

You can install the required packages using the following command:

```bash
pip install numpy pillow keras tensorflow h5py opencv-python-headless
```

## Usage

1. Download the Flickr8k dataset and place it in the appropriate folders as described in the program.
2. Download the InceptionV3 weights using the provided link and place them in the `~/.keras/models` directory.
3. Run the program using a Python interpreter:

```bash
python image_captioning.py
```

Replace `image_captioning.py` with the name of your program file if it's different.

4. Follow the prompts to provide an image path and view the generated caption.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
