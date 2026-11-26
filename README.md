# Heic2Jpg

A simple Python script that batch-converts `.heic` images to `.jpg` format using ImageMagick.

## Requirements

- Python 3
- ImageMagick 7 or later
- The `magick` command must be available in your system `PATH`

## Usage

1. Install [ImageMagick](https://imagemagick.org/).
2. Place `heictojpg.py` in the folder containing your `.heic` images.
3. Run the script:

```bash
python heictojpg.py
```

All `.heic` files in the current directory will be converted to `.jpg` files with the same names. Original images are preserved.
