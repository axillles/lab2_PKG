# Image Info Extractor

## Overview

Image Info Extractor is a simple Python application that enables users to extract and display metadata from image files. It uses the `PIL` (Pillow) library to read image properties such as size, DPI, color depth, and compression type.

## Features

- **Open Multiple Images**: Select multiple image files to view their metadata.
- **Open Folder**: Select a folder to extract metadata from all images within it.
- **Display Image Information**: Shows relevant details for each image in a structured format.

## Requirements

- Python 3.x
- Pillow library
- Tkinter (usually comes pre-installed with Python)

## Installation

1. **Clone the repository or download the script**.

   ```bash
   git clone <repository-url>
   cd <repository-directory>

Install the required packages:  
Make sure you have Pillow installed. If not, you can install it using pip:

```bash
pip install Pillow
```



## Usage

Run the application:

```
python image_info_extractor.py
```

Use the "Open Images" button to select one or more image files.
Use the "Open Folder" button to select a folder containing images.
The metadata will be displayed in the text area, including:

Filename
Size (Width x Height)
DPI (Dots Per Inch)
Color Depth (e.g., RGB, RGBA)
Compression type
Example Output

Filename                      Size            DPI         Color Depth     Compression
======================================================================================
image1.jpg                   1920x1080       300x300     RGB             JPEG
image2.png                   800x600         96x96       RGBA            N/A
Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements.

License

This project is licensed under the MIT License. See the LICENSE file for details.
