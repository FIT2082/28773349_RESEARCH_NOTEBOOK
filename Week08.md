# Week 8
## Modelling the signs in Unity
This week we tried to model the signs on a game object in Unity. We have been given a human model to use for our project, which removes the need to create our own model from scratch. 

In Unity, game objects have transforms, such as position, rotation and scale. For our purposes, we will only be manipulating thee rotation factor of the model. The model is set up with a heirarchy for each body. We will be focusing on the arms and fingers, so the heirarchy that we are interested in is:
* Shoulder
  * Arm
    * ForeArm
      * Hand
        * FingerBase
          * Thumb1
            * Thumb2
              * Thumb 3
                * Thumb 4
          * Index1
            * Index2
              * Index3
                * Index4
          * Middle1
            * Middle2
              * Middle3
                * Middle4
          * Ring1
            * Ring2
              * Ring3
                * Ring4
          * Pinky1
            * Pinky2
              * Pinky3
                * Pinky4

We the tried to set the rotation of each joint of a finger from the recording to the model. To set rotations, we need to use Quaternions. These are vectors that extend complex numbers and represent the quotient of two directed lines in a three-dimensional space [Wikipedia], and are difficult to calculate. Thankfully, both Unity and Leap Motion have calculated these vectors for us, and we only need to convert from LeapMotion Quaternion to Unity Quaternion. 

The next step seemed simple, to apply the rotation of each child compenent and set the transformation of the rotation. However, we encoutered problems with this. It appears that the transformed rotation of a parent component does not change the rotation value of its children. We now need to calculate an offset from each parent component in order to set the rotations correctly. We were not able to do this this week, so we will continue to work on this next week. We will ask Han for help, as it is his model which we are using.

## Ethics
We also submitted our ethics application this week. Dr Kirsten lodged it for us. 

We had to submit:
* The questions we plan to ask
* The poster with which we plan to advertise our study
* Our research statement and consent form

It will take approximately two weeks for it to be processed. Hopefully by then, we will have our system ready to be tested, so we can start collecting our data from the user survey, and be able to prove the effictiveness of our system.
