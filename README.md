# USB-Hub
In this project I learnt how to develop a USB hub using a Macondo guide.

Here is the link:[ https://pro.easyeda.com/editor#id=2e76f19754eb4b5d8cd38e7c9e5385ab](https://pro.easyeda.com/editor#id=2e76f19754eb4b5d8cd38e7c9e5385ab)

https://pro.easyeda.com/editor#id=2e76f19754eb4b5d8cd38e7c9e5385ab,tab=*c20d99a6ca90ac40

This is the OSHWLab link:  https://oshwlab.com/cheunagly/project_gvkruypc
The USB hub serves a simple role of connecting devices behind a USB together, by connecting 2 USBCs 2 USBAs to a hub IC and then to an upstream USBC, allowing charging and file transfer. Needing split chargers at home and a curiosity in electronics led me to be fascinated by this guide and decided to try develop it and learn more about circuitry.

As my first project, this quickly taught me how schematics work, such as netting, how to connect ships on an IC, and the structure of a pcb, and how there are multiple layers involved from silkscreen to ground and voltage layers and how they link together.

In this project, I faced many somewhat simple challenges. Starting from no experience, menat that I very easily was oblivious to issues like overlapping components and how to plan routing. At the start I imagined routing would be the biggest game of connect the dots I had ever played without realising I was able to use multiple layers for routing. I then also realised that the pin netting for the USB HUB IC could be changed while preserving functionality, to avoid overlapping wires.

At first this was definately difficult, but after the routing most things proved quite simple apart from some basic grounding errors.

This is the final schematic:

<img width="2362" height="1672" alt="SCH_Schematic1_1-P1_2026-07-08" src="https://github.com/user-attachments/assets/747a3cb8-a29d-41ec-a720-8f3831dcbc17" />

This is the final:

<img width="737" height="450" alt="image" src="https://github.com/user-attachments/assets/37b18ccc-693b-4eff-b9b6-b3a2f6f1bd30" />
<img width="731" height="441" alt="image" src="https://github.com/user-attachments/assets/2fb528a1-2aeb-4c0c-8f72-0f2da9cdb04d" />


This is the 3D render:

<img width="905" height="666" alt="image" src="https://github.com/user-attachments/assets/d99fd1cb-0725-4488-9208-1dc5657b133b" />
<img width="585" height="727" alt="image" src="https://github.com/user-attachments/assets/5a549a67-e14c-427f-bd11-c413eaa6fb3d" />
