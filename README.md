# link2

https://images.hindustantimes.com/rf/image_size_630x354/HT/p2/2019/08/08/Pictures/_6bda0940-b9ad-11e9-98cb-e738ad509720.jpg
import cv2
import matplotlib.image as mping
import matplotlib.pyplot as plt

#Read file
img1=cv2.imread('bb1.jpg')
img2=cv2.imread('leaf1.jpg')

#numpy add
fimg1 = img1 + img2
plt.imshow(fimg1)
plt.show()

#saving
cv2.imwrite('output.jpg',fimg1)
fimg2 = img1 - img2
plt.imshow(fimg2)
plt.show()
#saving
cv2.imwrite('output.jpg',fimg2)
fimg3 = img1 * img2
plt.imshow(fimg3)
plt.show()
#saving
cv2.imwrite('output.jpg',fimg3)
fimg4 = img1 / img2
plt.imshow(fimg4)
plt.show()
#saving
cv2.imwrite('output.jpg',fimg4)
