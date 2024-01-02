# MacTerminalBase64Decoder

## Overview
MacTerminalBase64Decoder is a Python script designed to decode Base64-encoded sections within macOS Terminal files, particularly `.terminal` files. It's especially useful for extracting and reading the configuration and settings data encoded in these files.

## Features
- Extracts Base64 encoded data from macOS Terminal files.
- Decodes Base64 data into a human-readable format.
- Handles binary plist data by converting it into XML plist format.

## Requirements
- Python 3
- Basic knowledge of terminal/command line usage.

## Installation
Clone this repository using Git:
git clone https://github.com/Str1ck9/MacTerminalBase64Decoder.git

## Usage
Navigate to the cloned directory and run the script with:
python3 decode.py [filename]

Replace `[filename]` with the path to your `.terminal` file.

## Example
python3 decode.py Pro.terminal

## TODO
- Reverse the process and convert back to base64?
