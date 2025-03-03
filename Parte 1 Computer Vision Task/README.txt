Part 1: Computer Vision Task - Object Detection & Tracking 

For the development of this task a computer vision model was trained. Inside the "Training" folder there are all the files used to train it, a code with the training steps and the results. On the other hand, the file named "Computer_vision_task.ipynb" is a small prototype of the developed solution. To run the code the next libraries are required:
 
	- ultralytics
	- cv2
	- plotly
	- numpy
	- threading
	- time
	- dash
	- json

When the code is runed, a window will automatically open, showing the camara of the computer. If burgers, pizzas or fries show in front of the camara, they will identified by the trained model, and the objects will be enclosed in a square. On the left top corner of the screen that shows the camara view, it will be displayed the count of the identified objects. At the same time, where the is running, a bar graph will appear showing in real time the number of identified objects. At last, to end the process it is necessary to press the 'q' key, when this happens, a txt file named "detection_results.txt" will be created in this folder. The file will contain a JSON with the summary of the count of the detected objects with its corresponding time stamp.
