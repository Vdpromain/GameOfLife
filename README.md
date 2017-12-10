Forked from [scienceetonnante/GameOfLife](https://github.com/scienceetonnante/GameOfLife)

# GameOfLife
GameOfLife In Python, used in my Youtube video https://www.youtube.com/watch?v=S-W0NX97DB0
Produces movie starting from a given pattern.
Requires numpy and matplotlib packages, and "ffmpeg" software for producing animations.
Can read RLE files as input patterns (http://www.conwaylife.com/wiki/RLE)

# Modifications

I used the argparse library, to add a linux like command line interface, to the script.

I modified the rle files, so they can embed parameters.

I added the "--rlefile_path" argument, to pass the file to read as an argument on command line. So you can use as follows:

  $python GameOfLife.py --rlefile_path path

I added the "--output_dir" argument, to direct output in a customized directory. The directory is automatically created, if it does not already exist. Its default value is: "output".
