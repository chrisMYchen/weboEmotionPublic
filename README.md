[Jibo SDK & API Documentation](https://developers.jibo.com/sdk/docs/)
# weboEmotion

What is Webo? Webo is an add on package of Skills for Jibo in order to interact with emotion. Using Jibo's built in camera functionality in conjunction with Microsoft's Emotion API, we are giving Jibo the ability to empathize, categorizing facial appearances into emotions for Jibo to interpret and react to appropriately.

##Live Demo
(To be updated)
https://youtu.be/TEBD9qVcGJE
https://drive.google.com/open?id=0B9ZcMb9O3z5JZXV6dFBNUktvdWc


##Skills

###Look At
This skill simply takes photos of the nearest person he is interacting with and processes their emotion. Then given this emotion, he will respond as if in conversation - mimicking the person's emotional state.

####SAD
If the person is Sad, he will make a slow, wide whirl back and forth and emit a soft purple glow. He will also say appropriately despondent phrases.

####NEUTRAL
If the person is Neutral, Jibo will perform his a straightforwards "nod" side to side emote, say a neutral phrase, and also emit a green glow.

####HAPPY
If the person is HAPPY, Jibo will perform an exciting, quick swing to both sides, speak appropriately enthused word responses, and emit a yellow glow.


##Dependencies
We use the following Node.js packages aside from the packages Jibo already uses
+ 'fs'
+ 'request'
+ 'node-oxford-emotion'

##Code to look at:
Start at /behaviors/main.bt

##Installation:
1. Clone this repo locally
2. Navigate to this directory via terminal and npm i (Must have node and node package manager)
3. Install JiboSDK through atom
4. Once registered/with proper login access, open project!
5. Generate Microsoft API Key https://www.microsoft.com/cognitive-services/en-us/emotion-api and replace line 27 in the first ExecuteScript with this key.
6. Run this skill!
