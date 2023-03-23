# yolov5-cpp
running yolov5 using onnx in C++ language 

Step 1 – Install Homebrew
https://brew.sh/
Go to the website and copy the link and paste in the terminal to install.
Step 2 – Install Opencv
  Go to terminal and type 
 
  brew install opencv
 
Step 3 – Create New Xcode Project
  Open X code and create a "macOS" - "Command Line Tool" - "C++"
 
Step 4 – Add Dynamic Libraries
  Right Click Project folder and "Add Files to ..."
 
  Press forward slash "/" on keyboard to type the folder path
 
  /usr/local/Cellar/opencv
 
  open your version folder and go to lib and select all Dynamic Libraries 
 
Step 5 – Add Header Search Path
Python
  Select your project folder and go to "Build settings"
 
  Select All and Combined 
 
  Search for "Header Search Paths" 
 
  Double click and enter the path (make sure to change your version)
 
 /usr/local/Cellar/opencv/4.5.0_5/include/opencv4
 
 make it recursive
