
Virtual Background Replacement (No Green Screen)

This is a beginner-level Python project that will allow you to replace the background behind the person in a webcam image with a virtual background image - no need to use a green screen!

In this program, we access the webcam to get live video, the program detects the person using MediaPipe's Selfie Segmentation and the program replaces the background in the frame using OpenCV .

 Features:

- No green screen required
- Real-time background replacement using your webcam
- Easy to implement and run on any computer system

Technologies Used:
Packages used ,
"opencv-python" -Used to access your webcam, process the frames, and display the images back to the screen .
"mediapipe" -Uses AI in the background to perform a segmentation task to detect the human in the frame .
"numpy" -Used to blend the original frame containing the human and the other frame created from the virtual background 

Prerequisites :
 -Python 3.7+ - PyCharm (or any Python IDE) 
 - A working camera 

Setup Instructions :
1. Open up PyCharm: 
 Create a project folder 
2. Add a background image : 
 Save your virtual background image in the project folder - Call it: "background.jpg"
 3.Install requirements :
 Open the "Terminal" in PyCharm and type, 
" pip install opencv -python mediapipe numpy"
Run the Python file 

These are the basic steps to follow through to run the program and stop it.

-Open projectname.py 
-Click the green Run button 
-Press q to quit the webcam window
