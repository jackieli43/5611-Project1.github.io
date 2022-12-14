# 5611-Project1.github.io
![unknown](https://user-images.githubusercontent.com/76919047/193730594-27db3b34-933c-4606-a7cb-1dd0ba36d5bf.png)
This is what the game looks like with the PRM nodes visible. You can also turn on the routes for the main agent and other agents(crowd sim).


PART 2

https://user-images.githubusercontent.com/76919047/193732679-f90f0e44-e7aa-4879-8c2c-b60e251829e9.mp4


https://user-images.githubusercontent.com/76919047/193733185-74d77098-0497-4a7f-9a85-ae6c0bc37c76.mp4

Video Explanations(one video has start and end location visible, other video does not):
- At the start ( Before 10 seconds), I am moving the start and end location
- In the middle (10 seconds - 20 seconds), I am placing more obstacles down.
- At the end (20 seconds - 30 seconds), I am showing the particle effects after the agent reaches its goal and how well the camera moves.
- Throughout the video after the 10 second mark, I move the camera alittle bit to show that the camera moves and that it's all in 3d.



Part 3

![image](https://user-images.githubusercontent.com/76919047/193735166-84667cbe-677f-472a-851d-0f43ff8e1ccf.png)

![image](https://user-images.githubusercontent.com/76919047/193734977-01fd1890-b924-4f54-b506-2818f328fa6e.png)

![image](https://user-images.githubusercontent.com/76919047/193736074-aeb2a4ab-6dad-4f60-ae76-3f4d23c0f3ac.png)

![image](https://user-images.githubusercontent.com/76919047/193736122-e9591dd3-3b83-4887-b026-3fecf6986a40.png)

Crowd Simulation:
- I can't post a video, because I have a limit of 30 seconds per video, and I honestly don't think my computer can render it properly in thirty seconds.
- There are sections of code I commented and above put "CROWD SIM!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!". If you uncomment them and run, it should show each unit moving and reacting to eachother.
- The reason the crowd simulation takes up so much computational power, is that everytime the units see that they might run into another unit, they try to recalculate a path which takes a chunk of time. I wasn't sure how to use TTC, because the other agents would run into obstacles if I did.
- I also put the images of the locations of where each place to uncomment in the code is.


Features I attempted:
-   Single Agent Navigation 
-   3D Rendering & Camera 
-   Improved Agent & Scene Rendering 
-   Incorporate Particle System 
-   User Scenario Editing+ 
-   Crowd Simulation
  
  
  
Difficulties I ran into:
-   The biggest thing I think I ran into was that my partner dropped the class near the middle/end of this project which really left me in a time scramble to put this together. I think if I had a partner throughout this project would have gone much better, but things happen I guess.
-   I didn't realize I could split crowd simulation and part 2 up, so I implemented a sort of crowd simulation into part 2 which honestly was really tough.
-   Since I incorporated crowd simulation into part 2, I kept running into issues where my program would slow down, since there were so many computations being done.
-   I havent used processing before, so it took alot to get used to.
-   I ran into the same issue of scene rendering destroying my computer as I tried to load a background image and have each obstacle have it's own image.
-   The code is a big mess, because I was handed a bunch of things I didn't write and thought I could just build on top of it. Turns out I can build on top of it, but it is really difficult to parse and understand.
-   For some reason, everything is a little laggy. Maybe its because I am running it on an older computer, but everything I do takes a second or so.



Sources:
- I got the idea of SphereLoc from https://github.com/erich666/T2Z/blob/master/src/ProjectT2Z/Animations.pde. Which made it easier for me to create spheres.

Tools/Libraries:
- I used Professors Guy's example code for many of the things such as the camera, object mesh, and PRM basics.
- I used the person I mentioned in sources Sphere information to make it easier for me to make spheres.




![image](https://user-images.githubusercontent.com/76919047/193736153-962a4b17-7697-4878-9529-9d8925ae2e6f.png)

If you uncomment this, you will be able to see the lines that each unit and agent takes.


