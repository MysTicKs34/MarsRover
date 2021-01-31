Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@MysTicKs34 
brkdmn
/
MarsRover
1
00
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
You’re making changes in a project you don’t have write access to. We’ve created a fork of this project for you to commit your proposed changes to. Submitting a change will write it to a new branch in your fork, so you can send a pull request.
MarsRover
/
README.md
 

Spaces

2

Soft wrap
1
# MarsRover
2
​
3
​
4
A squad of robotic rovers are to be landed by NASA on a plateau on Mars. This plateau, which is curiously rectangular, must be navigated by the rovers so that their on board cameras can get a complete view of the surrounding terrain to send back to Earth.
5
A rover's position and location is represented by a combination of x and y co-ordinates and a letter representing one of the four cardinal compass points. The plateau is divided up into a grid to simplify navigation. An example position might be 0, 0, N, which means the rover is in the bottom left corner and facing North.
6
In order to control a rover, NASA sends a simple string of letters. The possible letters are 'L', 'R' and 'M'. 'L' and 'R' makes the rover spin 90 degrees left or right respectively, without moving from its current spot. 'M' means move forward one grid point, and maintain the same heading.
7
Assume that the square directly North from (x, y) is (x, y+1).
8
​
9
### Input:
10
The first line of input is the upper-right coordinates of the plateau, the lower-left coordinates are assumed to be 0,0.
11
The rest of the input is information pertaining to the rovers that have been deployed. Each rover has two lines of input. The first line gives the rover's position, and the second line is a series of instructions telling the rover how to explore the plateau.
12
The position is made up of two integers and a letter separated by spaces, corresponding to the x and y co-ordinates and the rover's orientation.
13
Each rover will be finished sequentially, which means that the second rover won't start to move until the first one has finished moving.
14
​
15
### Output:
16
The output for each rover should be its final co-ordinates and heading.
17
​
18
## Input and Output
19
​
20
### Test Input:
21
5 5<br/>
22
1 2 N<br/>
23
LMLMLMLMM<br/> 
24
3 3 E<br/>
25
MMRMMRMRRM<br/>
26
​
27
### Expected Output:
28
1 3 N<br/>
29
5 1 E<br/>
30
​
@MysTicKs34
Propose changes
Commit summary
Create README.md
Optional extended description
Add an optional extended description…
 
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
