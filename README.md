# CT Heart Image Segmentation - Data Preparation Pipeline

This project is part of a medical imaging pipeline designed to preprocess and augment CT images and their corresponding segmentation masks, specifically for heart CT scans.


## ⚙️ Features

- Automatically loads and splits CT heart images and masks.
- Applies the following augmentations:
  - Horizontal Flip
  - Vertical Flip
  - Random Rotation (up to 45°)
- Resizes all images and masks to `512x512`.
- Saves processed data to a new organized directory structure.
- Masks are binarized after resizing (0 or 255).

## 🚀 How to Use

1. Place your dataset under the `data/train/` directory in the expected format.
2. Run the script:

```bash
python your_script_name.py


