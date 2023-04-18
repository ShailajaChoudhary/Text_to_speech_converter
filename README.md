# Text to Speech Converter

A simple Python program that converts written text to spoken words using the pyttsx3 library. The program also utilizes the pillow, tkinter, and os modules to create a user interface for the user to input text and hear the output.

## Overview

The Text to Speech Converter is a Python program that takes in written text as input and converts it into spoken words. The program utilizes the pyttsx3 library to generate the audio output, and also includes a graphical user interface created with tkinter to allow for easy input and output of the text.

## Installation

To use this program, you will need to have Python 3.6 or higher installed on your computer. You can download the latest version of Python from the official website: https://www.python.org/downloads/

Additionally, you will need to install the required Python modules: pyttsx3, pillow, tkinter, and os. You can install these modules using pip, the Python package manager:
```bash
  pip install pyttsx3 pillow tkinter
```
## Usage

To use the text-to-speech converter, run the text_to_speech.py script. The script will launch a tkinter user interface where you can enter the text you want to convert to speech. Click the "Play" button to hear the text spoken out loud.

```python
python text_to_speech.py
```
You can also use the speak.py script to speak a text string directly from the command line:
```python
python speak.py "Hello, world!"
```
## Acknowledgements

This project is based on the following resources:

 - [pyttsx3 documentation](https://pyttsx3.readthedocs.io/en/latest/)
 - [pillow documentation](https://pillow.readthedocs.io/en/stable/)
 - [tkinter documentation](https://docs.python.org/3/library/tk.html)
 - [os documentation](https://docs.python.org/3/library/os.html) 
