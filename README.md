Usage for 10bit data in LSB format and resolution 3840x2160 is like this:

./raw2rgb.py file.bin 3840 2160 --stride 7680

usage: RAW2RGB Converter [-h] [--stride STRIDE] [--frame FRAME] [--version]
                         filename width height

Convert Raw images into RGB format

positional arguments:
  filename
  width
  height

optional arguments:
  -h, --help       show this help message and exit
  --stride STRIDE  stride of the image (default: width of the image
  --frame FRAME    frame number to grab (default: index 0)
  --version        show program's version number and exit
