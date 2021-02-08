The code takes an input image, the image that is to be processeded at the start.
pic = cv2.imread('ImageName.datatype', 0)
However, this input image is also entered again in the "Non-Maxima Suppression" section, because I needed its dimensions to make an RBG version of it.
C = np.array(Image.open("ImageName.datatype").convert("RGB"))

The sigma for the edge detection is also at the start of the code.
However Tl and Th values are at the end of the code, they can be easily edited by just enter the values into the function call of hysteresis function.

Outputs are at the end of every section of code
cv2.imwrite('ImageName.datatype', Output)
