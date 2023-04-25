@mainpage

# Overview

This is a documentation website for my CSC 212 project, Recursive
Graphics.

We were tasked with implementing a variety of recursive graphics using
c++.

We chose to implement Koch's Snowflake, Sierpinski's Triangle, and
Hilbert's Curve.

The output of each of these c++ files is a text string, representing how
to draw each shape. We then use a python file, which will draw the shape
and the output will be a jpeg file displaying that drawing.

Feel free to look around the website to see our documentation and
resulting output for the given shapes!




# Recursive Graphics

Welcome to our Repo for our Final Project for CSC 212 at URI!

Within this repo we have added many files, including our .cpp files .txt files and .jpeg files



Instructions for compiling and running code:

1. Download the source files (SierpinskiTriangle.cpp, VonKoch'sSnowflake.cpp, and hilbertsCurve.cpp)

2. Compile the code, for example for VonKoch'sSnowflake.cpp (in terminal) 'g++ VonKoch'sSnowflake.cpp -o snow'

3. Run the code, for example './snow'

4. (Depending on the program) The program will then ask for the level of complexity for the drawing (enter numbers 1-5 (or whatever the program prompts user for), 1 being simple 5 being complex

5. The program will then print "Process is complete" 

6. The program made a new file eg. snowflake5.txt or triangle4.txt within the same directory as the source code

7. Copy all the contents from that text file

8. You can either test this code locally or through the use of our website (https://andrewcampbell15.github.io/recursivegraphics/)

9. If you choose to test locally you will need to download 'l-system-plotter.py' from our repo and run this code 'python3 l-system-plotter.py YOUR_SNOWFLAKE/TRIANGLE_TXT_FILE_NAME.txt <output file name> 60'
  9a. If you would like to test hilbert's curve, change the last value '60' to '90' since the turns will be 90 degrees.

10. If you test using the website simply paste the txt file documents where it says 'instructions' (line 21). In line 23 if you are using either the Sierpinski Triangle or VonKoch's Snowflake set the 3rd argument to 60. For the Hilbert Curve set it to 90. Once that is complete hit the run button.
  
11. Enjoy your shape!
