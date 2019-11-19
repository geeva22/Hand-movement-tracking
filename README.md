Description:
	
Hand movement tracking is an important feature of many computer vision applications. In this application, A histogram-based approach is used to separate out the hand from the background frame. Thresholding and Filtering techniques are used for background cancellation to obtain optimum results.



Why: Problem Statement:
	
	The main reason for doing this project is to help blind and physically challenged peoples. They can’t use computers and laptops as normal people use. By means of this project, they can control the laptops by their hand movement. The problem with the above approach is that changing light conditions and skin colors can really mess with the skin detection. While on the other hand, Histogram tends to be more accurate and takes into account the current light conditions.


How: Solution description:
	
In an application where you want to track a user’s hand movement, skin color histogram will be very useful. This histogram is then used to subtract the background from an image, only leaving parts of the image that contain skin tone. A much simpler method to detect skin would be to find pixels that are in a certain RGB or HSV range.

	Now that we hold a skin color histogram we can use it to find the components of the frame that contains skin. OpenCV provides us with a convenient method, that uses a histogram to separate features in an image. I used this function to apply the skin color histogram to a frame.
  
Resources Required:

	Tools used:  Anaconda - Python version 3.6 and OpenCV.
