# CrewComms

**An immersive crew voice simulator for Flight Simulators.**

License: *Creative Commons Zero v1.0 Universal*

<img align="top" width="400" src="https://github.com/ProIntegritate/CrewComms/blob/main/Demo.png" />

*Crew Comms* is a standalone executable built upon .NET framework 4.0, it is a basic panel that just play sounds as you press a simulated airplane panel. Since i mostly play Airbus A320, that is what it drew inspiration from, and also to look more like part of the simulator than an external program.

It basically consists of one executable (Soundplayer.exe) and 9 wave files, each wave file corresponds to the button on the panel. 

# Files:

Program package:<br/>
**CrewComms1.0-Soundplayer.zip** <br/>

Required sound files:<br/>
**1.wav.zip** <br/>
**2.wav.zip** <br/>
**3.wav.zip** <br/>
**4.wav.zip** <br/>
**5.wav.zip** <br/>
**6.wav.zip** <br/>
**7.wav.zip** <br/>
**8.wav.zip** <br/>
**9.wav.zip** <br/>

Source code is not required to download, but it is available in the **CrewCommsv1.0.source.zip** file <br/>
(This is the first and final version, if you want improvements - you are free to bransch this project and make them yourself, i'm not interested in maintaining this as i just wanted basic functionality - so you go ahead and do that).

# A bit about how it works

As seen on the picture below, I used no button controls in the program and instead used pictureboxes with a triggable event (.Onclick) to make it look better, a button control would have looked really ugly and had broken immersion. It uses an instance of a mediaplayer control to play the sounds. If there was an MP3 library on every Windows box, i would have used that instead.

<img align="top" width="300" src="https://github.com/ProIntegritate/CrewComms/blob/main/SoundPlayer.png" />

The sounds used by the program is:

1. (De)Boarding sound
2. Pre flight announcement (Cabin crew)
3. Safety Demonstration (Cabin crew)
4. Prepare for Takeoff message (Captain)
5. Post takeoff announcement (Cabin crew)
6. Turbulence alert message (Captain)
7. Descent announcement (Cabin crew)
8. Prepare for landing message (Captain)
9. Post landing announcement (Cabin crew)

# How to use it

- Make sure all .wav files are in the same path as the executable, then start the executable. Click on each button to play it's respective sound, if there are no sounds playing, then you probably have no sounds in the folder as described above or you may have some problems with your sound device.

- The program does not require a specific simulator to run, but i built it for the A320 and MSFS 2020. It can be started regardless of the state of the simulator, once you are done with it, you can end it by clicking on the top right X.

- In the simulator, you ALT+TAB to get the program up front, click on a button, then click on the simulator again to focus back on the simulator. The sound will keep playing, even in the background.

That is basically it.

Uninstall instructions: Delete all files. It has no dependencies and it does not register anything. All it requires is .NET framework 4.0 and that should probably already be installed on your system. If it isn't there (like if you are running Windows 7 or something) grab it from Microsoft official site and install that.

# Testimonials:

What is used to create this:

1. I generated audio speech with: https://ttsmp3.com/?
2. The chime sound was downloaded from - https://freesound.org/people/nachosose/sounds/244583/
3. The Button click came from MSFS2020 itself, it's basically the same in all sims.
4. Audacity was used to make the voices sound as if the crew were talking through a crap PA system.
5. I modified and used some scripts from: https://airodyssey.net/reference/inflight/
