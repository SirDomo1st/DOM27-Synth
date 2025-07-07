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

After that I started putting my pcb layout together but lo and behold, I had some more issues. As i had already spent alot of time fixing other stuff, I will come back to this.
![image](https://github.com/user-attachments/assets/17317ec5-a379-4ef4-a58c-e8dcc8af6fc9)
![image](https://github.com/user-attachments/assets/0452a510-21be-4fac-a60c-64ab2616fef7)

Time spent: 1h

---

June 30th: Layout and copper
I finished the layout of my pcb and connected all the components with copper
![image](https://github.com/user-attachments/assets/e3ba3bc4-3049-4d9f-b145-38ff2fd38572)
![image](https://github.com/user-attachments/assets/d68d10f7-11b3-46a7-838b-a035b5743d28)

Time spent: 1h

---
July 1st: VCF pannel 3D model
I created the pannel for the VCF the same way I did for the VCO. I made sure to add tolorances and also holes for the screws, for when I screw it into the case
![image](https://github.com/user-attachments/assets/76fb4acc-8a32-44d2-a2e7-c9344e52c77d)
![image](https://github.com/user-attachments/assets/1d49c4d1-bdc0-46a0-9520-3d040d235b84)
With that, the DS-20 VCF is now complete. 
I also realised that in my 45hp case, only 44hp would be filled up. This meant I also had to model a 1hp pannel. This was alright though as I can use it for decoration.
![image](https://github.com/user-attachments/assets/b9497c11-6c12-426c-b99b-d2225f9fc122)
The penultimate module I would like to make is a VCA (voltage controlled amplifier).
Time spent 1h:


---
July 1st: the VCA research
As mentioned before, the next module I would like to create is a voltage controleld amplifier (VCA). There is a very common saying in moudlar sythnesis that goes "you can never have too many vca's". This is because they are immensely useful for shaping and modulating sounds.
I started by deciding what features I would like on my VCA. I only really have 2 main requirments, 4 VCA's on 1 pannel and mixing section.
I went to look online for some schematics I could reference but I came up short. The only schematics with my requirements I could find where too complicated for me to understand currently or contained componenets that were either too expensive or hard to get.
However, with combining a single VCA, copying it 3 more times and adding a mixer (with the help of a friend) I was able to create a schematic I thought would work.

Time spent: 0.5h

---
July 1st: VCA Schematic
Using my schematic from before I created the layout for the VCA. Here it is:
![image](https://github.com/user-attachments/assets/0a258c5d-1647-4a41-ac91-52700ea4345b)
It features 3 seperate VCA's and a mixer

Time spent: 1h

---
July 1st: VCA pcb layout & copper
I then took this into the PCB editor and started playing with the layout. This was actually quite challenging as it was very condensed and tough to make space for everything. In fact, initally by board had 4 VCA's however I had to strip one out to make space
![image](https://github.com/user-attachments/assets/17ea8d05-8419-4981-8fb8-d81389ce541b)
I then also routed all the copper
![image](https://github.com/user-attachments/assets/ad847458-de10-4e7c-ba1a-b4ac7096e8ff)
Time spent: 1.5h

![image](https://github.com/user-attachments/assets/dfa9b1b4-0d58-4f22-a89d-f356f8575f23)

---
July 1st: VCA CAD
I exported the pcb and imported it into fusion 360 to design the pannel the same as before
![image](https://github.com/user-attachments/assets/5aae53b6-a655-4084-8e0e-2947de679016)

![image](https://github.com/user-attachments/assets/a2c2a5ec-e466-4972-944f-afbb21a15545)

Here is how everything looks at this point in time
![image](https://github.com/user-attachments/assets/fdbeaecc-6d6a-4830-bc71-7f15493b87f7)
![image](https://github.com/user-attachments/assets/9e932dd7-9ce7-4441-9222-1ae4354b657f)

Time spent: 1h

---

July 3rd: Whole LFO pannel
For my last pannel I wanted to create an LFO (low frequency oscilator). This would allow me to controla parameters on other modules hands free.
As this is my last pannel I was able to create this fairly quickly.
I started with 30 minutes of research. I found that it would be ideal for me to have a dual LFO module for more functionality

I then spent 1 hour putting this into KiCad, assinging footprints, creating the layout of my PCB and then exporting.
![image](https://github.com/user-attachments/assets/bc9ac73b-d914-4b49-8d4c-e9885f8d9154)
![image](https://github.com/user-attachments/assets/f92d9c23-5b41-47bc-ae18-f24cd84ba02e)
![image](https://github.com/user-attachments/assets/2152b6cd-293f-416d-a318-cd66f270a97b)

I then exported this into Fusion 360 and moddled the pannel:
![image](https://github.com/user-attachments/assets/e5b97682-e178-4e84-a69b-d73b891dfa11)
![image](https://github.com/user-attachments/assets/df5eff9c-3938-4081-ad8a-008495a78e97)

With that, the basis for each pannel is done. Here is how it looks:
![image](https://github.com/user-attachments/assets/e4060516-d10b-4067-9f2c-0aa665365627)
![image](https://github.com/user-attachments/assets/f254d1b4-f3b2-459f-bbd7-6f27ecbac8b3)

Time spent: 1.5h

Now that all my pannels are complete, I now need to go back on my old work and optimise it to use less components to save money, I need to label the value of each component to make soldering much easier and I will also need to verify with friend and on forums that my schematics and layouts work.
---

June 4th: Labeling everything
I started by going back onto my first module, the VCO.
I went through and copied the values from the schematic onto the corresponding parts
I also redid the copper as I notices some issues, and labeld other parts more clearly
I also did this for the VCO.
![image](https://github.com/user-attachments/assets/17143ab4-50b9-4f06-a48b-001e742754a7)
![image](https://github.com/user-attachments/assets/0b74a0ac-cdbf-4b2f-bb67-427607a43b9b)
Time spent: 1h

---

June 7th: Labeling everything continued
I did the same thing as before but on the other 2 modueles
![image](https://github.com/user-attachments/assets/37be5d73-dde8-478d-9ac8-0fa493a5fe8e)
![image](https://github.com/user-attachments/assets/07191062-0c23-4746-a653-a4278b05967b)

Time spent: 1h

---


