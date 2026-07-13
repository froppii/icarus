## 22/04/2026

I tried looking at components I needed and stuff!! I still don't know how to pick a speaker etc, but we'll figure it out. I made a sketch of what i want the case to look like ish and we decided on some components to use like the display and battery, also a bit of CAD to figure out the dimensions!


**Time spent : 1**

**Total time : 1**

## 24/04/2026
started making the pcb!!! still a bit confused on what to do but a few youtube vids and google searches later im starting to get the hang of it. after looking a bit i decided to use the esp32 s3 wroom 1 yay!!

**Time spent : 2**

**Total time : 3**

## 06/07/2026

progress after nearly 2 months, tried to continue figure out what modules and components to use. looked into how and what i need to charge lipo batteries, decided on the tp4056 chip components and found out i needed a voltage regulator. wanted to go with ht7333 but found out that the output current is too low(250-300mA, esp32 needs atleast 500mA) so switched to ap2112k (much stabler, 600mA)

<img src="Screenshot 2026-07-07 001041.png" width="500">

**Time spent : 3**

**Total time : 6**

## 07/07/2026

more schematics work yay....! searching for an alternative to the DAC i initially wanted to use (TAS5721) because turns out its not a headphone amplifier, speaker only. decided to abandon the idea of having speakers for the mp3 player and doing headphone only. planning on adding a new bluetooth audio module but alas the search continues


**Time spent : 4**

**Total time : 10**

## 08/07/2026

holy lockin. i learned what pullups are... the ones with resistors and some electronics basics because i have the memory of a goldfish. looked into lipo charging circuits but found out you can use these magical things called power management ics, which basically has everything in one. theres so little resources on the axp2101 pmic im using so ill be giving up on it for now and get back to it eventually sob. good news is i figured out how to wire the sd card!!! yippie!!!1 and the usbc to some extent

<img src="Screenshot 2026-07-09 001708.png" width="500">
<img src="Screenshot 2026-07-10 214921.png" width="500">

**Time spent : 8**

**Total time : 18**


## 10/07/2026

today i spent more time doing schematics, was home the whole day so i locked in!! i figured out how to connect my DAC, aswell as the whole power system. abandoned the pmic because it was too complex for me sob,, oh also the display!

<img src="Screenshot 2026-07-10 201130.png" width="500">
<img src="Screenshot 2026-07-11 000000.png" width="500">

**Time spent : 14.5**

**Total time : 32.5**

## 11/07/2026

more locking in, for 15 hrs!! wowie. finished my schematics, and started routing. twas my first time routing something with this much parts and i had to redo it once because it was spaghetti. it is also my first time doing ground fills TwT. routing is like 50% done hoping to finish tmr (my aunt woke up from me working so i had to stop TwT)

<img src="Screenshot 2026-07-11 203053.png" width="500">
<img src="Screenshot 2026-07-12 024707.png" width="500">


**Time spent : 15**
**Total time : 47.5**

## 12/07/2026

even more routing, this thing isnt finishing istg. i also learnt how to use vias and all, mostly how to route properly this is starting to get a little fun. today is just routing again. (my aunt woke up from me working again so i also had to stop early)

<img src="Screenshot 2026-07-13 015434.png" width="500">

**Time spent : 7**
**Total time : 54.5**

## 13/07/2026

I FINISHED ROUTING!! YAY!! now we on to cadding!! cadding!! cadding!!

<img src="Screenshot 2026-07-13 102828.png" width="500"> 
<img src="Screenshot 2026-07-13 103815.png" width="500">
<img src="Screenshot 2026-07-13 105010.png" width="500">

**Time spent : 10**
**Total time : 64.5**
