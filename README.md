# Pong500
Simple Pong game that uses Computer Vision to allow for 500 people to play at one time. 

## The Code
Using two webcams, each trained on 250 students sitting in the bleachers in our high school gymnasium. 
Using OpenCV-python to capture video frames. They are analyzed by counting the pixels in each of 250 rectangular slices
that are above a threshold for blue and a threshold for red. Each player holds a card with the red side to the camera
and their team's paddle moves UP 0.4% faster (0.4% * 250 = 100%). Similarly for blue.

We are applying for a Guinness World Record! After the record determination is complete, I will post the python code.

Here is a YouTube video showing the game in action: [Video Title](https://www.youtube.com/watch?v=PxMoWTW0YuE)

