```bash
$ ./meme_maker -h
usage: meme_maker [-h] --text-1  --text-2  --source  [--dest]

optional arguments:
  -h, --help  show this help message and exit

required arguments:
  --text-1    Top text
  --text-2    Bottom text
  --source    Meme template image (soure) path
  --dest      Distination image file path
```

## Install

In a virtual environment, run `pip install -r ./requirements.txt`. There's only 1 dependency required, which is Python Pillow lib.

Make sure to `chmod +x ./meme_maker` or at least run it with Python entrepreneur, e.g `python meme_maker [...]`.

## Example

```bash
./meme_maker --text-1 'is daylight savings time' --text-2 'a form of time travel?!?' --source ./template.jpg
```

Another example: specify destination image path to save the meme to:

```bash
./meme_maker --text-1 'is daylight savings time' --text-2 'a form of time travel?!?' --source ./template.jpg --dest ./meme.png
```