# Marker info
The pattern images are each 512x512, but the detected part is the inner black 
square, which translates to 1 unit in the virtual world. 
The inner black square takes up 80% of the width/height of the entire image, 
so to cover the entire image (including the outer white area up to the thin 
black border), use a cube that is 1.25 units on a side. 