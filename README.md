# Implementation-of-Canny-edge-detector-and-Harris-corner-detector

There are 2 notebooks implemented in google colab notebook.
The main notebook is Canny_Edge_detector_and_Harris_corner_detector.ipynb

It contains the whole solution to the given problem.
Just upload the image you want.
write the name of the image with the extension as a string 
infront of the imgname variable. just as depicted below.

3rd cell
imgname='Your image name here'

Then simply select Runtime -> Run all.


The other notebook visualising_corners.ipynb is simply for visual purposes.
it superimposes the Corner_NMS image on the original image to highlight
the corners.
For this purposes simply change the name of the image saved in the Corner_NMS
to avoid confusion.
then upload the original image as well as this image with this notebook.
then just make these changes:

a='Original image name'
b='Modified image name '


Then simply select Runtime -> Run all.


All outputs are saved in the output folder. Most of them are 
displayed in the report.

The Corner_NMS images are renamed by suffixing them with 1 as they are
reused in another notebook visualising_corners.ipynb. In order to avoid
any confusion.

