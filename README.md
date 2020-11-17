# Mini-Mac
Hakintosh build from spare parts.
(More photo's on the final version)
![alt text](https://github.com/Remco17/Mini-Mac/blob/main/IMG_1015.JPEG)
# Parts
- CPU: INTEL G4560
- GPU: ASUS RX 470 4GB OC
- RAM: 16GB 3200MHz ( My main pc was 32 gb, it had 4 sticks. I took 2 so i can build this, the board does not actually supports 3200MHz, but 2400MHz, so i will lose 800MHz)
- MOBO: ASUS PRIME B250-PLUS
- CASE: MasterBox Q500L ATX
- PSU: Weird one, got it from a friend. Does not have a brand, as far i can see.
# Configuration
I used clover for this build. It is currently working very stable. Will transistion to OpenCore because it is better an handeling BigSur and is faster, and cleaner.
# Does iMessage and Facetime work?
It currently does, Apple Support only had changed something in my account so it could work. Didn't work before because i wasn't using a verified serial number, now it is. 
# Whats the goal of this project, if you have a better main pc?
macOS only supports very old Nvidea GPU'S, my main pc has a 2060 Super which is not supported. I wanted to build this machine for using facetime, for calling to people using my headset. Also for learning Swift. Windows does not support calling from a iPhone.  --- Also when i move out, i want to give this PC or Mac to my parents. Depends on which OS the rather want, probaly Windows. 
For gaming and such i will use my main pc
# BigSur
Ones i have made a stable config for OpenCore i will finally update to BigSur
# Opencore
Opencore currently works, but with very very bad peformance on BigSur.
# Issues
OpenCore on BigSur gives extremly bad peformance. If i make a whole new config, so the sanity checker says it's perfect it won't boot at all. But the 'bad' version of opencore works with the bad peformance, while that is a older config file with the new version of OpenCore which shouldn't work.
# TO-DO list
- [X] Also need to buy a extra display-port cable so i can connect the second monitor to the mac. 
- [X] Finding a damn screw for the m.2 drive in the system ( Currently without screw, it works, but that's not really good practice. And has a change of falling out over time without screw. So gotta find a scre :D ) 
- [X] Convert Clover to Opencore, so it will be futureproof, and even more stable for BigSur.
- [X] Find the right kexts or changes in the configuration so macOS can read temps. 
- [ ] Making OpenCore stable, so the peformance is reliable.
