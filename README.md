## Bat Player ##

This code slows down, fades-in and de-noises bat calls to make them audible. 

**Main function parameters**
- play (boolean): add a play button to the window
- write (boolean): write computed audible spectrogram in separate file
- display (boolean): show spectrogram
- low-cut (float): frequency of high-pass filter
- factor (float): factor by which the sound should be slowed down (personal preference for 75)
- order (int): order of high-pass butter filter
- short (boolean): only play and display the first minute of the file (after slowdown)
