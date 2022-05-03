CLI based PPM editor with the following features (done using quadtrees):
- image compression into a very compact file that can be later turned back into a compressed image (basically useful for storage)
- conversion of the previously mentioned format into a usable compressed image (that takes less space than the original, but more than the file)
- horizontal and vertical rotation

To use the program, run the executable with one of the following input templates:
- ./executable -c treshold input output (for compressing into the compact format, where treshold affects the level of compression, the lower the more compressed the image will be)
- ./executable -d input output (for turning the compact format into a PPM image)
- ./executable -m h/v treshold input output (for rotating a file horizontally/vertically and compressing it at the same time)
