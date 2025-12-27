# Draw Square Snap! CS-Principles
My second Snap! project for CS Principles. This is a simple algorithm made in Snap that draws a square.

#### How I Made it
After creating my first project which was guided by my teacher, he instructed me to create a program via Snap! that draws a square using the pen blocks without being guided like the first project. He also recommened trying a rectangle. I've dabbled in Scratch before so I already knew how to do this. A pen down at Start, add a repeat that repeats 4 times for each side of the square, activate the pen, move a certain amount, and then rotate 90 degrees to continue to the next side. Finally a pen up outside of the loop to stop the drawing. This program did what my teacher instructed but... it was kind of boring and I wanted to challenge myself. 

1. I first added a wait function between the lines drawn so you could see the square being drawn (rather than it nearly instantaneously appearing). 
2. I noticed in Snap the board doesn't clear when you stop the program, so I then found out about the clear function and added it just below the on start block. Now the program cleared the lines on start to prevent line clutter.
3. The sprite in Snap starts at an angle which resulted in it drawing a diamond rather than square, so I added a point in direction command set to 90 degrees so it would start straight. It now drew a proper square.
4. I knew my teacher had recommended trying a square and a rectangle. I didn't want to make to separate files for people to download just for a rectangle, so I built it into the script! I added an ask block to ask if you'd like to draw a rectangle or square, which is something I used in my first project. I then added an if block that checks to see if your answer was S or R. If it was S, it draws a square. If it was R, it draws a rectangle. If it's neither, it tells you to only type S or R and to restart the program.

All of this took me about an hour. It was mainly part 4 that gave me a hold-up since I was experimenting a little. That's it! Thank you for reading this.

#### How to Run it
If you see this and you'd like to view my project follow these steps:

1. Download the "Draw Square (CS Principles).xml" file in this repository.
2. Go to https://snap.berkeley.edu/
3. Press the Run Snap! Now button.

<img width="1091" height="658" alt="{E4597494-E598-47BB-A248-CD4399D81792}" src="https://github.com/user-attachments/assets/52da74db-88b6-4677-8dfb-2b4e21f91026" />

4. You can either drag the file onto the Snap window or you can import it, up to you. Follow the steps below to import it. If not, skip to step 8.
5. In the top left of the screen hit the small file icon.
   
<img width="441" height="124" alt="image" src="https://github.com/user-attachments/assets/cfc43d3d-a664-4fa8-86ce-1012f820df04" />

6. Find import and select it.

<img width="276" height="314" alt="image" src="https://github.com/user-attachments/assets/da8aed23-a879-445f-8ea0-aa8e1405f9af" />

7. Find the file you downloaded, load it, and you have my project now!
8. To run the program click the green flag in the top right corner of the window.

<img width="598" height="431" alt="image" src="https://github.com/user-attachments/assets/6d05130f-b53a-47fd-bfeb-6b968983fbe8" />

You're all set! 
