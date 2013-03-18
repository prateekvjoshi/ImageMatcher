Image Matcher
============

This code implements OpenCV based image matching using SURF descriptor. This algorithm extracts SURF descriptors from one image and matches them with the descriptors extracted from the other image. I have included sample input images along with this project. There is a file called "CMakeLists.txt". This file will be used to build the project (if you have built OpenCV using cmake). If not, just use the .cpp file in your project and build it. To build using command line, follow the steps below to get it up and running:

	$ cmake .
	$ make
	$ ./main image1.jpg image2.jpg

The output will be displayed on a window and you can see the matcher stats on the terminal.