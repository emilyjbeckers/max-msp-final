# max-msp-final

Loop audio files and apply different effects to them. Meant to be controlled with Nintendo Switch Joy-Cons. 

## What Am I Looking At?
Max/MSP is a visual programming language that is used for music and audio proccessing. Because it's a visual programming language, the files here aren't the actual code and are meant to be read by the proprietary programming environment developed by [Cycling '74](https://cycling74.com/products/max/). If you're really curious about about seeing the 'code', you can download a free trial from their website and poke around. I've also created a standalone application of this project which corresponds with the first commit which was too large to push to Git but can be downloaded from my [Google Drive](https://drive.google.com/file/d/1EJ9vZdI83cqwautQzsfYwHSt45z8m6G_/view?usp=sharing). 


## Effects
Group 1:
- Chorus
- Flanger
- Phasor

Group 2:
- Time scaling
- Pitch shifting
- Playback speed (affects time and pitch)

Group 3:
- Reverb

Group 4:
- Panning

## Controller
The interesting part of this project (in my opinion) was working with the controller. I'm using `hi` to read input. This does not report the accelerometer data. The abstractions in the joycon folder are made to work in any project using the Joy-Cons, and they're free to be used as long as I'm credited. 


## Ideas for the Future
What I have was enough for the final project itself, but as it is it's not particularly useful to a user. Having 'tracks' or samples that could be either looped or triggered by button presses and each 'track' having effects applied independently would be more interesting to a user, but beyond the scope of what I could accomplish in the time I had. 

