# JPEG to PNG Converter

A command-line tool designed to simplify the conversion of JPEG images to PNG format. This tool is intended for users who prefer a quick, script-based solution for image conversion without needing additional software. Developed with user-friendliness in mind by Alireza Fazeli.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Author](#author)
- [License](#license)

---

## Overview

Converting images between formats can sometimes require complex software. This command-line tool simplifies the process by allowing you to convert JPEG images to PNG in just a few steps. The script is lightweight, efficient, and perfect for users who often work with image files and prefer a CLI-based workflow.

## Features

- **Simple Interface**: Easily convert JPEG files to PNG format using command-line arguments.
- **Help Command**: Built-in help message to guide users on command usage.
- **Flexible Paths**: Specify custom input and output paths for conversions.
- **Lightweight**: Requires only Python and Pillow, with minimal system overhead.

## Requirements

This tool is built using Python and the **Pillow** library, which provides image processing capabilities.

- **Python** 3.x
- **Pillow** library for handling image files

Ensure these dependencies are installed before running the script.

## Installation

1. **Clone the Repository**
  Clone this repository to your local machine:
  
  ```bash
  git clone https://github.com/alirezafazeli8/jpeg-to-png-converter.git
  cd jpeg-to-png-converter
  ```
  

2. **Install Dependencies** Install the required dependencies using the provided `requirements.txt` file:
  
  bash
  
  Copy code
  
  `pip install -r requirements.txt`
  
  Alternatively, if `requirements.txt` is unavailable, manually install **Pillow**:
  
  bash
  
  Copy code
  
  `pip install Pillow`
  

## Usage

To convert a JPEG file to PNG, use the following command format:

bash

Copy code

`python main.py <input_file_path> <output_file_path>`

Replace `<input_file_path>` with the path to the JPEG file and `<output_file_path>` with the desired output path for the PNG file.

### Display Help

For a help message outlining the command syntax:

bash

Copy code

`python main.py -h`

### Example Usage

1. **Basic Conversion**
  
  bash
  
  Copy code
  
  `python main.py "D:/images/photo.jpg" "D:/images/photo.png"`
  
2. **Help Message**
  
  bash
  
  Copy code
  
  `python main.py --help`
  
  This will display a welcome message along with usage instructions and links to the author's profiles.
  

## Examples

### Example 1: Converting a Single Image

Suppose you have an image saved as `example.jpg` in the `Pictures` folder on your desktop. To convert this image to PNG format and save it in the same folder:

bash

Copy code

`python main.py "C:/Users/YourUsername/Desktop/Pictures/example.jpg" "C:/Users/YourUsername/Desktop/Pictures/example.png"`

### Example 2: Error Handling

If you try to convert a non-JPEG file or provide an invalid path, the script will raise an error. For instance, if the input path does not exist:

bash

Copy code

`python main.py "invalid_path.jpg" "output.png"`

## Troubleshooting

- **File Not Found Error**:
  Ensure that both input and output paths are correctly specified and that the input JPEG file exists in the given location.
  
- **Permission Denied Error**:
  If you're running the script in a restricted directory, you may need administrative privileges to read/write files.
  
- **Unsupported Format Error**:
  This tool only converts JPEG files. Attempting to convert other formats may raise errors.
  

## Author

Made with ❤️ by Alireza Fazeli to make image conversions straightforward for everyone.

- [LinkedIn Profile](https://linkedin.com/in/alirezafazeli)
- [GitHub Repository](https://github.com/alirezafazeli8)

Feel free to connect or follow for more projects!

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.

---

> **Note**: This tool was created for personal or educational use. Ensure to follow best practices when using it for large-scale or production purposes.

This `README.md` provides a comprehensive guide, including setup, examples, troubleshooting, and background on the script. Let me know if any more sections should be added!
