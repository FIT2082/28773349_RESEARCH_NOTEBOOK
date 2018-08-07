# Week 2
## Initial meeting
This week we met with Dr Kirsten and Han, her PhD student, with whom we will be working. Dr Kirsten has done much research in teaching sign langauge to hearing people, and to young children. Han is currently completing his thesis, and is working on developing feedback methods for people learning how to sign, in order to improve and deliver more accurate signing.

## The system
The system currently uses a Kinect to detect its users movements, but it lacks precision. It does not recognise fine motor movements or details, such as finger positions. Moreover, the Kinect does not work well when there are other people within its  range of vision, or when the users are wearing bulky clothing such as jackets. 

There is a range of feedback options available to users. Feedback from the system entails a visual depiction of the user's avatar and their motion, contrasted with the correct motions expected. Han has implemented adynamic time warping (DTW) algorithm to match precisely speed, commencement and conclusion of the user's attemt at signing. 

## Our aims for the project
We hope to implement a few improvements to the system, such as 

* Incorporating virtual reality support into the program, to enhance the user's feedback experience. The current system displays the feedback on a 2D screen, and it is diffuclt to visualise the teacher's movements from a single angle. Our aim would be to have a 3D model around which the users can walk around and observe feedback from a range of angles.  

* Incorporating the virtual reality handsets into the program, in order to more accurately track gross and fine motor movements. Currently movements are tracked by the Kinect, which has already proved to be inaccurate. Perhaps with the integration of a physical motion sensor with an accelerometer, we can more precisely follow the user's movements. 

* Implementing a scoring system, where users are rewarded for more accurate signing. Currently, the system delivers feedback, but the experince lacks excitement, and by adding a game / competition aspect we may be able to encourage better signing.

* Write an algorithm to read the movements of the user and determine what sign they are making. However, given the time frame for the project, it may be difficult to implement this. Dr Kirsten reccomends implementing a particle swarm algorithm to compare handshapes. 

## Software /platforms / framework
The system uses Unity, a framework which requires us to write C# code. I do not have any experience using Unity, but I hope that the learning curve is not too steep. 
