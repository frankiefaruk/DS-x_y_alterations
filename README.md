# Decent Sampler Preset Coordinate Adjuster

A simple Python script for adjusting the `x` and `y` coordinates in Decent Sampler `.dspreset` files. This script allows users to easily update the graphical layout of the Decent Sampler interface by shifting the positions of various elements based on user-specified adjustments.

## Features

- Adjust `x` and `y` coordinates in `.dspreset` files.
- User-specified adjustment values for both coordinates.
- Skips adjustment if a coordinate value is not a valid integer.
- Saves the adjusted file in the same directory with a `_adjusted` suffix.
- Provides a graphical interface for file selection and input using `tkinter`.

## Requirements

- Python 3.x
- The following Python modules, which are typically included with Python:
  - `xml.etree.ElementTree`
  - `tkinter`
  - `logging`
  - `pathlib`

## Usage

1. Clone or download the script and save it as `adjust_dspreset.py`.
2. Make sure Python 3.x is installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
3. Run the script using a terminal or command prompt:
   ```bash
   python adjust_dspreset.py
