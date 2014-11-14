Steganography in Java
=====================

I implement the Steganography algorithm which embeds secret information into a “cover image”

You can embed text information or a picture into a cover image.

The secret information is hidden from the top left (0, 0) pixel to the right and then to the next line below. I use the last digit of each pixel to store each digit of the character. To extract secret information from the cover image, read the picture, extract last digit of the pixel from (0, 0). Eight pixels can form one character. These implementations just redo the steps of embedding the information into the cover image.
