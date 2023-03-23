# yolov5-cpp

##  * **<p align="center"> 🍅🍅yolov5 c++ object detection onnx🍅🍅</p>** *

I have tried it on xcode of macos (macbook-air 13)

* **Step 1 – Install Homebrew** *
https://brew.sh/
Go to the website and copy the link and paste in the terminal to install.
* **Step 2 – Install Opencv** *
  Go to terminal and type 
  
```shell
brew install opencv
```
  
 
* **Step 3 – Create New Xcode Project** *
  Open X code and create a "macOS" - "Command Line Tool" - "C++"
 
* **Step 4 – Add Dynamic Libraries** *
  Right Click Project folder and "Add Files to ..."
 
  Press forward slash "/" on keyboard to type the folder path
 
  
```shell

/usr/local/Cellar/opencv

```
 
  open your version folder and go to lib and select all Dynamic Libraries 
 
* **Step 5 – Add Header Search Path** *
Python
  Select your project folder and go to "Build settings"
 
  Select All and Combined 
 
  Search for "Header Search Paths" 
 
  Double click and enter the path (make sure to change your version)
  
```shell

/usr/local/Cellar/opencv/4.5.0_5/include/opencv4

```
 make it recursive
 
 ![running the examples](https://github.com/animeesh/yolov5-cpp/blob/main/static/detection.png)


[❤️ Star 🌟👆🏻 this repo to support me if it does any helps to you, thanks ~ ]
