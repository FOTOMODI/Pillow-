# Pillow-
colors
from PIL import Image, ImageOps

image = Image.open('input.jpg')
inverted_image = ImageOps.invert(image)

inverted_image.save('output.jpg')
