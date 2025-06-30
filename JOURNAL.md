---
title: "DOM27 Synth"
author: "Domo"
description: "A modular synthesiser"
created_at: "2025-06-13"
---
June 14th: Started my research
I started to learn about analouge VCO's (voltage controlled oscialtors). I watched some youtube videos - here are some things I learnt:
-The components that go into making a square wave and sawtooth wave oscilator
-How electrical charge can move around a circuit to create pitch and noise

I have decided I am going to start with a VCO module with 2 types of tone, pusle and saw.
I am also keeping in mind other modules I may want to make in the future, such as:
-VCA
-Envelope
-LFO
-Squencer (maybe?)
-VCF
-Mixer

Here are some videos I watched:
-[This 4 part series on VCO's](https://www.youtube.com/watch?v=QBatvo8bCa4)
-[Understanding Voltage Controlled Oscillators](https://www.youtube.com/watch?v=kuo6Q0LuHNM&t=285s)
Total time spent: 2h
---
June 14th: Designed first mock of circuit diagram
![image](https://github.com/user-attachments/assets/d49c6159-f723-4ca2-8aff-d6fe6d3145dd)
-This is cicuit diagram for my VCO
-I also learnt about different types of components that go into making a circuit

Total time spent: 2h
---
June 16th: Added PMW modifcation and started to think about power
I found a circuit design for Pulse Width Modulation. I think this would be a good edition to my first VCO so I added it
![image](https://github.com/user-attachments/assets/996bc7d3-2a11-4343-816b-0eca4343fc95)
I also did some research into how to power my module and I added this 
![image](https://github.com/user-attachments/assets/7a879222-d634-4c3f-b445-59367e5db896)
I also picked the name for my VCO - The ✨"Klajdiscope"✨

Total time spent: 2h
---
June 18th: Figuring out layout of module
![image](https://github.com/user-attachments/assets/b7e92c2a-2a81-420e-85cf-6ebfada003bd)
I spent quite a significant amount of time working on where everything should go, so I can make it as useable and understandable as possible.
I also spent some time figuring out what I actually need phyiscal inputs and potentiometers for on the module. I concluded that R3, R5, R7 & R9 do not need dials, as they have constant resistance

Total time spent: 1h
---
June 21st: Footprints and Finalising layout
The first thing I had to do was assign footprints for each component in my circuit, so that when they are placed on the PCB they have the right holes. Because this was my first time, this took me a fair while as I wanted to make sure that I was doing everything right.
![image](https://github.com/user-attachments/assets/c6a2bb05-f537-4245-abf3-2664cd728ba4)
After that, I copied the layout I had made previously by dragging the footprints around. This is what I was left with:
![image](https://github.com/user-attachments/assets/9b2bbf0a-86d1-4d3c-ab3f-f8329e38811d)
Here is a photo of my pcb:
Total time spent: 1h
![image](https://github.com/user-attachments/assets/63b05e84-cbb9-4271-9207-5624a767d7f0)
![image](https://github.com/user-attachments/assets/1ac51430-a149-4c26-8193-a3dd4d0f86be)
Next to do is the copper on the PCB

---
June 22nd: Copper
I had to create copper lines to connect each of my components on my PCB. I did a whole bunch of research and found somethings out. e.g: copper lines cant touch
Doing this took a while as I kept on having to go back and undo things to make way for other things
Eventually I got it down though, here is what it looks like 
![image](https://github.com/user-attachments/assets/a552a5fd-6619-418c-bb1d-d92ab20af7c9)
Time spent: 1h

---
June 23rd: Creating the top plate
On this day I wanted to create the top plate/ face of my VCO module.
The first step to do this was to install 3D models for each of my components on my PCB and then import that into Fusion 360
![image](https://github.com/user-attachments/assets/88c39691-42da-438e-877e-5e7cfd7bab7f)

Next, I followed the outlines of the components on the board and also looked up the real world dimensions to create the correct size holes that I need.
I also decided to add a bit of tolerance (+2/3mm) to ensure that everything fits
![image](https://github.com/user-attachments/assets/672f69b0-8b03-4eea-83c2-2a46463bfcd4)
![image](https://github.com/user-attachments/assets/7a0a4bb6-21e0-4910-9c47-87ccc5542395)
![image](https://github.com/user-attachments/assets/4a2e5ed4-ccb7-43aa-a6e6-ab2dfbeac99a)

With that, my first module (the VCO) is now complete ✅. The next one I would like to make is an LFO (low frequency oscilator)
During my research, I found that this was a very useful module to have in a modular synth system as it enables me to modulate parameters hands free and in time with a beat.

Time spent: 1h

---

June 27th: VCF schematic
On this day I created the schematic for my VCF (voltage controlled filter)
![image](https://github.com/user-attachments/assets/2e5aa582-fb8e-484b-9dfa-d36b62a667ef)

Time spent: 1h

---
June 30th: Fixing all my errors!
Today I went to start work on my pcb layout, however i realised i had a ton of mistakes. Loads of things were labeled and named incorrectly. After watching lots of youtube videos and asking about, I finally got it fixed!
![image](https://github.com/user-attachments/assets/43550cd5-5f48-4f76-8b9e-b4322212abec)
Time spent: 1h












