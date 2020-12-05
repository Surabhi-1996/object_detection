# Russian License Plate Blurring

## We are using Cascade Classifier(Haar Cascade) to detect the object in an image.

- Our goal will be to use Haar Cascades to blur license plates detected in an image!
- Read in the car_plate.jpg file using OpenCV.
- Visualize the image using matplotlib.
- Load the haarcascade_russian_plate_number.xml file.
- Create a function that takes in an image and draws a rectangle around what it detects to be a license plate.
- Create a blurred version of the ROI (the license plate) we will want to paste this blurred image back on to the original image at the same original location.
