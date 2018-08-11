# Week 3

## Approach to the project
This week, Andrew and I further discussed how we would like to approach the project, and decided what aspects we would like to focus on. On Friday, we met with Dr Kirsten to review these further. We discussed many hardware options:
* Occulus Rift [https://www.oculus.com/rift]

  We will definitely use this VR headset and handset to implement our project. Dr Kirsten has one in her office which we will use. It comes with hand held controllers as well, which we would also like to try. The advantage of all components coming from the same box is that the target user will be able to use our application without the need to source and configure multiple input devices. This also reduces the risk a particular component becoming obsolete or unavailable and reduces the initial cost for the consumer.
 * Leap Motion sensor [https://www.leapmotion.com]

    This is a small sensor designed to work at close proximity (80cm) to track hand movements. It has two cameras and three infrared LEDs. The cameras have wide angle lenses, which results in a large space in which movements can be detected. Some image resolution adjustments are performed locally on the device itself, and then the data is sent via USB cable to the software. We hope to use this to teach the alphabet, as these signs are performed in front of the user
* Gloves
  
  We discussed the possibility of using gloves with motion and touch sensors. These provide the advantage of being able to track finger positions when the user's hands are outside of the Leap Motion sensor's field of view. Some signs are performed with the user's hands above their head to the side of their body. However, the gloves we have access to are wired, and require an Arduino [https://www.arduino.cc] to work. We have decided to leave this option for now.
  
## Bringing the Leap Motion sensor home
Han gave me the Leap Motion sensor to take home over the weekend. After downloading the required software, I was able to run demo projects, which gave me a sense of how powerful the Leap Motion is. I aim to test the distance at which movements can be detected. I hope to be able to set up the Occulus Rift next week and use as input, the Leap Motion sensor. 
