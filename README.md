# CrewComms

*An immersive crew voice simulator for Flight Simulators.*

<img align="top" width="400" src="https://github.com/ProIntegritate/CrewComms/blob/main/Demo.png" />

Binary package: **CrewComms1.0.zip**
Source code: **CrewCommsv1.0.source.zip**

Crew Comms is a standalone executable built upon .NET framework 4.0, it is a basic panel that just play sounds as you press a simulated airplane panel. Since i mostly play Airbus A320, that is what it drew inspiration from, and also to look more like part of the simulator than an external program.

It basically consists of one executable (Soundplayer.exe) and 9 wave files, each wave file corresponds to the button on the panel. 

**1,2,3
4,5,6
7,8,9**

<img align="top" width="300" src="https://github.com/ProIntegritate/CrewComms/blob/main/SoundPlayer.png" />

I used no button controls in the program and instead used pictureboxes with a triggable event (Onclick) to make it look better.

The sounds included are:

1. (De)Boarding sound
2. Pre flight announcement (Cabin crew)
3. Safety Demonstration (Cabin crew)
4. Prepare for Takeoff message (Captain)
5. Post takeoff announcement (Cabin crew)
6. Turbulence alert message (Captain)
7. Descent announcement (Cabin crew)
8. Prepare for landing message (Captain)
9. Post landing announcement (Cabin crew)

#Testimonials:

1. Generate audio speech: https://ttsmp3.com/?
2. The chime sound - https://freesound.org/people/nachosose/sounds/244583/
3. Button click - from MSFS2020 itself.
4. Audacity was used to make the voices sound as if the crew were talking through a crap PA system.
5. Modified some scripts from: https://airodyssey.net/reference/inflight/
