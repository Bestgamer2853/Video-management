video player as a pop up window using python

explanation:

The video media player is made using tkvideoplayer library 

first we need to install the library using pip install tkvideoplayer

line 1-3: to import required modules 

line 5-8: to set the title of the window,background color and the dimensions of the window

line 11-13:to open the video file in read # line 13 specifies file must be a mp4

line 14-17: if file is not None then file.name and videoplayer variables made global and file.name assigned to filename

line18-19: providing video path

line 20-21: using pack() to pack video,show on screen and play it

line 25-27:defining the play button and its location

line29-31:defining the stop button and its location

line 33-35:defining the stop button and its location

line 39-42: heading modification

line 44-45:open button

line 47-48:play button

line 50-51:stop button

line 53-53:pause button

line 57:while code is running and window is open looks for clicks on buttons
