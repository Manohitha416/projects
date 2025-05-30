# projects

# 🖼️ Background Remover and Replacer

This Python script downloads an image from a URL, removes its background using the `rembg` library, and places the subject onto a new background image. The result is saved as a final composite image.

## 📸 Features

- Downloads subject and background images from URLs
- Removes background from the subject image using AI (`rembg`)
- Applies filters and enhancements (blur, sharpen, brightness, contrast)
- Pastes the subject onto the background
- Saves both intermediate and final results

## 📁 Output Structure


## 🛠️ Requirements

Install dependencies with:

```bash
pip install rembg requests pillow

How to Run

Make sure you have Python 3 installed.

Save the script as main.py (or any name you like).

Run the script:

python main.py

The final image will be saved at: masked/final_image.jpg

Notes
You can change the subject and background image URLs in the script.

Adjust filter settings to fine-tune the appearance.

Uses rembg with alpha_matting=True for better edge refinement.

Example URLs Used
Subject: https://images.alphacoders.com/126/1267661.jpg

Background: https://sportsfields.info/wp-content/uploads/2023/04/Real-Madrid.jpg