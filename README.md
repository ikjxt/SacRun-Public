# SacRun-Public
SacRun is a game that I developed during my CSC 133, Object-Oriented Computer Graphics, course. Although I have worked on the game outside of class, I can not publish the code as future students may copy my work and this would violate my course agreement. This being said, I have a demo on youtube, along with this detailed ReadMe to showcase my project.

# Tools 
I used Eclipse IDE to code and simulate an Ipad, along with CodeNameOne API for Java GUI functionalities. The entire project is done in Java and I used Github for version control. Outside of these three tools, nothing else was needed or used.

# Game Layout And Controls
The main character of this game is a student trying to navigate around campus and get to class. While doing this, the student gets dehydrated, bumps into other students, and has to use the bathroom. All students are empty triangles, and the playable character is the solid triangle. Each lecture hall is a blue rectangle, each bathroom is a green rectangle, and each water fountain is a blue circle. While playing the game, you must manage your hydration, water intake, and absences. Hydration must not fall below 0, this will decrease each second and can be restored to 100 by going to a water fountain (blue circle). Each time you do this, your water intake will increase but it must not exceed 100, this can be dropped to 0 by using the bathroom (green rectangle). Lectures will randomly generate in each lecture hall (blue rectangle), and you must make it to each lecture before it ends or you will gain an absence. You can not exceed 3 absences, drop below 0 hydration, or let your water intake exceed 100, as this will result in losing the game. Bumping into other students results in a conversation, which will delay the player for a certain amount of time depending on the type of student. Each respective delay is listed below, along with the associated student type.

Here is the display when the game is started: (233)
![image](https://github.com/ikjxt/SacRun-Public/assets/68973747/a4d6d7fd-4bc2-4bf3-bb19-3956f4290231)

There are also students (clear triangles) that behave certain ways all over the screen. Each student has their own unique characteristics, which effects how they move. The stats and positions of all the students are outputted to the console. The students and their unique movement patterns are:
- Student Strategy: Randomly alternates between 1 of 3 movement patterns (Horizontal, Vertical, Confused), 2 second delay.
- Student Biking: Moves 3 times faster than normal students, 2 second delay.
- Student Confused: Random movement direction, 2 second delay.
- Student Friendly: Less than normal delay, 1 second delay.
- Student Happy: 25% chance the students speed will double for a while, 2 second delay.
- Student Angry: Longer than normal delay, 4 second delay.
- Student Car: Only moves horizontally or vertically, 2 second delay.
- Student NonStop: Does not stop player, no delay.

Here is the output to the console: (242)
add image of console output here.

The controls can be executed by either pressing the buttons on the left hand side of the screen or using your keyboard. If you choose to use your keyboard, the controls are:
- 'W' key : Starts player movement.
- 'S' key : Stops player movement.
- 'A' key : Move to the left.
- 'D' key : Move to the right.
  
# App Navigation
Main Page: The main page, the game will automatically open up to this page. (233)

Left Drop Down Menu: This menu can be opened by clicking the button indicated by three lines above the game buttons on the left hand side of the screen. (234)

Exit Button: This will prompt the user to exit the game or continue playing. (236)

About Button: This pop-up appears when you press the about button on the upper right hand side of the screen. (tbd)

Bottom Left Description: This part of the screen will indicate what is currently occuring, such as any collisions. (239)

# Video Demo
Interested in seeing a video demo of the game? [Click Here](https://youtube.com)
