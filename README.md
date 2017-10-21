# InnerStrength



 MazeViewer class
 
 Program to read in and display a maze and a path through the maze. At user
 command displays a path through the maze if there is one.
 
 How to call it from the command line:
 
      java MazeViewer mazeFile
 
 where mazeFile is a text file of the maze. The format is the number of rows
 and number of columns, followed by one line per row, followed by the start location, 
 and ending with the exit location. Each maze location is
 either a wall (1) or free (0). Here is an example of contents of a file for
 a 3x4 maze, with start location as the top left, and exit location as the bottom right
 (we count locations from 0, similar to Java arrays):
  
 3 4 
 0111
 0000
 1110
 0 0
 2 3
 

Course - CSCI455x:Programming Systems Design - Spring 2017
