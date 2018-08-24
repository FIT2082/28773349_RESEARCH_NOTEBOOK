# Week 5
## Using the Leap Motion with the Oculus
On Tuesday Andrew and I used the Oculus for the first time. We did so in Dr Kirsten's office, as she provided us with a computer and a space to set it up along with the sensors used with the Oculus. Our goal for the day was to use the Leap Motion with the Oculus.

To attach the Leap Motion to the front of the Oculus, we needed to use a mounting bracket, which was not provided with the device. To work around it, we used duct tape as a temporary solution.

Our next step was to download the asset packages for the Leap Motion to install in Unity. Doing so enabled Unity to recognise the Leap Motion, and as a result, when the headset is worn, the user can see their hands on the internal screen of the Oculus. 

Andrew took the Leap Motion home and was able to track the movements of its users hands. The api and documentation can be found here https://developer-archive.leapmotion.com/documentation/csharp/devguide/Leap_Hand.html and here https://leapmotion.github.io/UnityModules/

## Meeting with Dr Kirsten and Han
Today we met with Dr Kirsten and Han. We discussed how we would like to move forward with the project. We all agreed that we would use the alphabet. Because 24 of the 26 signs are static, we considered placing a static image of the sign on screen and then allowing the user to see their hands and match their handshape to the sign. Andrew and I also discussed the possibility of measuring the error in the user's performed sign, by calculating the distance from each joint to the joint of the model. 

We also discussed our plan for the coming week. 

* Create a storyboard for our project. We need to dicuss the design of each "scene" and what the user will be required to do
* Consider how we will present the signs to our users. Will we teach the letters in alpahbetical order? How will we know when to move on to the next letter? Will we sign the alphabet song? How do we handle static signs and dynamic signs?
* Propose research questions for our user based research. This will be used when submitting our ethics, which we will do next week
* Compile a list of signs that we will need modelled by a native signer. Dr Kirsten has found a native signer and an interpreter to model the signs for us. We need to organise a time to record these models
* Investigate how to use a Perception Neuron with Unity. Han has advised us that we will be able to do this with Unity, so that the file formats will be compatible. We will be using the PN to record the signs made
