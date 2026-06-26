# HEIC to JPG Converter

A small Python 3 script that batch-converts `.heic` image files to `.jpg`
format in the current directory using [ImageMagick](https://imagemagick.org/).

Tested on Windows 10.

## Requirements

- **Python 3**
- **ImageMagick** — install it from <https://www.imagemagick.org/>
  The script calls the `magick` command, which is the unified CLI shipped
  with ImageMagick 7+.

## Usage

1. Place the script (`heictojpg.py`) in the folder containing your `.heic`
   photos (or copy your `.heic` files next to the script).
2. Run:

   ```bash
   python heictojpg.py
   ```

Every `.heic` file in the same directory is converted to a `.jpg` with the
same base name, leaving the original files untouched.

## Notes

- The script operates on the *current working directory* (`.`), so either
  run it from the folder with your images or update the `directory` variable
  inside the script.
- Requires the `magick` executable to be available on your system `PATH`.