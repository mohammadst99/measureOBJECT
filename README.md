# measureOBJECT
in this vide you can use just a paper A4 to measure anything

# Libraries

import cv2

import numpy 

libraries ( python-opencv , numpy )


# Test Video
![](https://github.com/mohammadst99/measureOBJECT/blob/main/test.gif)

# Explain Code

first we need to capture our VIDEOcamera and set the SIZE of the VideoCamera 

then we apply filters ( Gray , Blur , Canny , dilate , erode ) so that we can find contours in our VideoCamera

then we can find our A4 paper as biggest contours and we can pic this part as change perspective and warp to show it as a seprate window

then we again find biggest contour but at this time we find this biggest contour in new warpimage ( on A4 )


