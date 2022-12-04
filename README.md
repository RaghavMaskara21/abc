1
(A)Take a color image and perform following conversions:
i) RGB to Gray
ii) RGB to index
iii) RGB to Binary (with and without predefined function)
(B)Construct Black image, White image, Black in White, White in Black image
(C)To plot 2D function f (x, y) =asin(u(x)*x+v(y)*y), where u and v any random


2
Take a color image & perform the following operation on gray scale image:
(A) Brightness Increases or Decreases
(B) Contrast Increases or Decreases
(C) Negative Image
(D) Take two color images, convert into grey scale images, resize them and perform addition, subtraction, multiplication, and division operations.


3
Image Transformations: Take one color image, convert it into a grayscale image and perform the following transformation operations:
a) Log transform (for c=10 and c=30)
b) Power law transform (c=1) (For dark image, λ=0.6, 0.2 ) ( For brighter image, λ=4, 8 )
c) Contrast stretching


4
Take one color image, convert it into a gray-scale image and perform the following transformation operations:
i i) Gray level slicing (with and without background)
ii ii) Bit Plane slicing


5
Write a program to perform histogram equalization for a given color image with and without pre- defined function. Also perform the histogram matching. Perform local histogram equalization using neighborhoods of size 3x3 on given image.


6
Take Grayscale or binary image and perform the following Morphological operations. 1. Erosion
cv2.erode(img, kernel, iterations=1)
2. Dilation
cv2.dilate(img, kernel, iterations=1)
3. Opening
cv2.morphology Ex (img, cv2.MORPH_OPEN, kernel)
4. Closing
cv2.morphology Ex (img, cv2.MORPH_CLOSE, kernel)


7
Take Grayscale or binary image and perform the following Morphological operations.
1. Morphological filtering – Opening followed by Closing
2. Hit and Miss Transformation cv2.morphology Ex (img, cv.MORPH_HITMISS, kernel)
3. Boundary Extraction
4. Thinning
5. Thickening


8
Perform various Spatial domain filtering techniques on below-attached image (filter.tif)

Apply filter operation with a different kernel size of 3x3, 7x7, 11x11,15x15 and 21x21.
i i) Low pass filtering
ii ii) High pass filtering
iii iii) Weighted average filter

9
Frequency domain analysis (Part-A):
Consider an image and perform the following operations:
1. Discrete Fourier Transform (DFT) using Equation 2. Verify the implemented function of DFT with inbuilt function (Hint: np.fft.fft2, np.fft.fftshift or cv2.dft(), cv2.idft()) 3. Plot magnitude and Phase spectrum (Hint: magnitude: 20*np.log(np.abs()), Phase: np.angle()) 4. Apply shifting operation and observe the magnitude and phase spectrum 5. Apply rotation and observe the magnitude and phase spectrum (Hint: np.rot90())


10
Frequency domain analysis (Part-B): Consider two images. Find the magnitude and phase spectrum of both images. Reconstruct the image using magnitude of first image and phase of second image and vice-versa.

