# Object_Detection_Using_Colours

We'll use OpenCV to detect objects in an image through a rudimentary method of using its colors.. A series of operations will be performed to detect if an object is present in the image. If so, the largest object will in the image will be highlighted and a green circle will be drawn around it to indicate its position in the image.

##Dependencies

* openCV
* matplotlib
* numpy
* math

You can use [pip](https://pip.pypa.io/en/stable/) to install any missing dependencies. And you can install OpenCV using
[this](http://docs.opencv.org/2.4/doc/tutorials/introduction/table_of_content_introduction/table_of_content_introduction.html) 
guide.

##Usage

Open the notebook 'blue_shirt_demo.ipynb' and run the cells.
To test custom images:
1. add YOUR_IMAGE to the folder 'image'
2. modify the path for loading your image `image = cv2.imread('images/YOUR_IMAGE.jpg')`


##Credits

Credits for this code go to [alexlouden](https://github.com/alexlouden/strawberries/blob/master/Strawberry%20working.ipynb) and Siraj Raval for his video on "How to do Object Detection with OpenCV".
