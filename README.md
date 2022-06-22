# link2

https://images.hindustantimes.com/rf/image_size_630x354/HT/p2/2019/08/08/Pictures/_6bda0940-b9ad-11e9-98cb-e738ad509720.jpg
import cv2<br>
import matplotlib.image as mping<br>
import matplotlib.pyplot as plt<br>
<br>
#Read file<br>
img1=cv2.imread('bb1.jpg')<br>
img2=cv2.imread('leaf1.jpg')<br>
<br>
#numpy add<br>
fimg1 = img1 + img2<br>
plt.imshow(fimg1)<br>
plt.show()<br>
<br>
#saving<br>
cv2.imwrite('output.jpg',fimg1)<br>
fimg2 = img1 - img2<br>
plt.imshow(fimg2)<br>
plt.show()<br>
#saving<br>
cv2.imwrite('output.jpg',fimg2)<br>
fimg3 = img1 * img2<br>
plt.imshow(fimg3)<br>
plt.show()<br>
#saving<br>
cv2.imwrite('output.jpg',fimg3)<br>
fimg4 = img1 / img2<br>
plt.imshow(fimg4)<br>
plt.show()<br>
#saving<br>
cv2.imwrite('output.jpg',fimg4)<br>
