## Image Conversion with OpenCV and Matplotlib

This project demonstrates how to convert images using OpenCV and Matplotlib. It includes various image processing techniques and visualization methods.

### Features
- Convert images between different formats.
- Apply filters and transformations.
- Visualize results using Matplotlib.

### Requirements
- Python 3.12.4
- OpenCV
- Matplotlib
- jupyter notebook

Here's a sample `README.md` file for your GitHub repository:

---

# Image Processing with OpenCV and Matplotlib

This demonstrate basic image processing techniques using OpenCV and Matplotlib in Python. The project includes loading a color image, converting it to grayscale and binary formats, and converting an RGB image to CMYK format. The results are displayed using Matplotlib.

### Requirements

Ensure you have the following libraries installed:

- `opencv-python`
- `numpy`
- `matplotlib`

You can install these using pip:

```bash
pip install opencv-python numpy matplotlib
```

## Project Structure

- `dog.jpg`: The image used for processing.
- `image_processing.py`: The main script containing the image processing code.
- `README.md`: This file.

## Usage

1. **Load the color image**: The script loads an image in BGR format using OpenCV.
2. **Convert the image to RGB**: OpenCV loads images in BGR format by default. The script converts it to RGB for correct color representation in Matplotlib.
3. **Display the original color image**: The RGB image is displayed using Matplotlib.
4. **Convert the image to grayscale**: The script converts the RGB image to grayscale.
5. **Display the grayscale image**: The grayscale image is displayed using Matplotlib.
6. **Convert the grayscale image to binary**: The grayscale image is converted to a binary image using a threshold value.
7. **Display the binary image**: The binary image is displayed using Matplotlib.
8. **Convert RGB to CMYK**: The script converts the RGB image to CMYK format, displaying each channel (Cyan, Magenta, Yellow, Black) separately.

## Running the Script

To run the script, execute the following command:

```bash
python image_processing.py
```

This will display the original color image, the grayscale image, the binary image, and the individual channels of the CMYK image.


