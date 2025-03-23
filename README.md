# Image Upscaler with Timer

This Python script upscales images by a custom factor using the Pillow library, includes a progress bar, and measures the time taken.

## Features
- Upscales images with a user-defined scale factor (default: 4x)
- Displays a smooth progress bar during processing
- Calculates and displays the total time taken
- Handles errors like missing files or invalid inputs

## Requirements
- Python 3.12
- Pillow library (`pip install pillow`)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/theFoxCost/image-upscaler-timer.git
   cd image-upscaler-timer
   ```

2. Install dependencies:
   ```bash
   pip install pillow
   ```

## Usage
Run the script with:
```bash
python image_upscaler_timer.py
```

### Input
- Enter the image file name (default: `thumbnail.png`)
- Enter the upscale factor (default: `4`)

### Output
- Saves the upscaled image as `thumbnail_up.png`
- Displays a progress bar and the time taken

## Example
```bash
Insert name of picture (default: thumbnail.png): my_image.jpg
Enter upscale factor (default: 4): 2
Upscaling my_image.jpg from 800x600 to 1600x1200...
[==========] 100%
Upscaling completed in 3.45 seconds.
Operation Done ✅
```

## Error Handling
- If the file is not found → `Error: Image file not found! ❌`
- If the upscale factor is invalid → `Error: Please enter a valid number for the upscale factor! ❌`
- For unexpected issues → shows the error message

## License
MIT License

---
Made with ❤️ by theFoxCost


