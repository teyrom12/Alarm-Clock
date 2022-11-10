# Alarm-Clock
This program reads a time that you insert and plays a sound when the time comes. 

To run properly you will need to install the playsound module with this command:

  'pip install playsound'
  
I do not recomment to install the latest version, instead install the version 1.2.2 with the command:

  'pip install playsound==1.2.2'
  
If you already have installed the latest version of the playsound module try uninstalling it first with this command:

  'pip uninstall playsound' and then press 'y' to proceed, after that try installing the version I recommend.
  
*All commands are for Windows*

At L19 make sure to replace: 'Your\Sound\File\Path\Here.mp3/mpeg' with the proper path to the sound you wish to be played. 
The playsound module supports windll.winmm. WAVE and MP3, MPEG also works. 

More of the playsound module on: https://pypi.org/project/playsound/
