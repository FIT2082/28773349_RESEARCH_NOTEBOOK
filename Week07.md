# Week 7
## Recording system
Last week we discovered that the Perception Neurons were not accurate enough. As a result, we had to use the Leap Motion to record the model signs.

Using the LM API, we were able to develop a system that can take snapshots of the detected hands, or multiple frames like a video. Most of the letters in Auslan are static, while letters 'h' and 'j' require the signer to move their hands. Our system works in this way:
* A key press is detected from the keyboard, and a new directory named with the key that was pressed is created. Intuitiveley, when recording the letter 'a', we press 'a' on the keyboard.
* If the letter is lower case (ie. shift was not held down simultaneously),we then save the the left and right hand data, which includes positional data of each joint in the hand. 
* If the letter is upper case, we record each position of the hand for each frame for the duration of the recording. We save this data twice, in two ways:
  * We save a new file named the timestamp of the recording for each frame. The file contains the hand data
  * We create a new file that contains an array of HandFrame objects (just the hand data and the timestamp)
 
 After recording the signs we can load the hand data and replicate the hand position. Currently, we haven't developed a representation of the loaded hand.
 
 ## Recording with Ramas
 Ramas is Deaf and offered to help us model the signs for our project. He came on Thursday and he signed the alphabet for us
 
 ## Meeting with Dr Kirsten
 We met with Dr Kirsten on Friday. She gave us a sample of and explanatory statement and sample interview questions for us to use when submitting our ethics for our user study. Since ethics approval takes two weeks, we aim to submit it soon, allowing us time to conduct our user study. 
