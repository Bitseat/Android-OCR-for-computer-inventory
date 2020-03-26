# Android-OCR-for-computer-inventory
Problem statement: Using Android camera take an image and do an OCR to extract the serial number, id and computer brand of computers
in Excellerent Technology Solutions Ethiopia delivery center.

The images to capture look like the image below.

![Image](image1.png)
image here

What we need is to register the information displayed on the images into an excelsheet as follow

![Record](image2.png)
excel sheet here

User interface that calls the Camera
1. Character extraction
Extract characters one by one from the captured data. We can do this with Tesseract. 
Tesseract is an optical character recognition engine for various operating systems. 
It is free software, released under the Apache License, Version 2+++.0. And Tesseract Tools for Android 
is a set of Android APIs and build files for the Tesseract OCR and Leptonica image processing libraries.

2. Comparison against dictionary
Each of the extracted characters is compared with registered characters for identification.

3. 

