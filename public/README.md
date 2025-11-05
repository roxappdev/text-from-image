# Tesseract.js OCR Demo

Demo page for text recognition from images using Tesseract.js library.

## Files

- `index.html` - Main page with description and link to demo
- `ocr-demo.html` - Main demo page for text recognition

## Setup

1. Make sure dependencies are installed:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

3. Open in browser:
   ```
   http://localhost:3000/public/
   ```

## Features

- Image upload via input type="file"
- Supported formats: PNG, JPG, JPEG, BMP, GIF
- Text recognition in Russian and English languages
- Preview of uploaded image
- Recognition progress display
- Copy recognized text to clipboard
- Error handling

## Technologies

- Tesseract.js - OCR library
- HTML5 File API - file handling
- CSS3 - styling
- JavaScript ES6+ - application logic

## Usage

1. Open the demo page
2. Click "Choose File" and upload an image with text
3. Wait for recognition to complete
4. Copy or use the recognized text

## Notes

- Requires running server (cannot open files directly via file://)
- First use may take time to load language data
- Recognition quality depends on source image quality