# HSR Special Pass Lite (Chameleon Lite clone)  
Yet another hardware version of [Chameleon Lite](https://github.com/RfidResearchGroup/ChameleonUltra)    
Demo video: [Bilibili: 给 Chameleon Lite 做个崩铁的星轨专票皮肤](https://www.bilibili.com/video/BV1Na4y127yF)   
  
![微信截图_20240114183821](https://github.com/libc0607/hsr_nfc_pass_lite/assets/8705034/f4c7b6d1-df54-4522-a926-51eec8dec7c2)  

![微信图片_20240114151503](https://github.com/libc0607/hsr_nfc_pass_lite/assets/8705034/fb797637-c9df-494d-a9c7-0f8af7e6f458)  

## Hardware 
The schematic of this version is same to the original one, with only few footprint changes.  
See [OSHWHub: libc0607/hsr_pass_lite_v1p1](https://oshwhub.com/libc0607/hsr_pass_lite_v1p1)   


If there's any registration wall, you can try this [exported version](https://github.com/libc0607/hsr_nfc_pass_lite/blob/main/ProProject_hsr_pass_lite_2024-01-15.epro) on Github.   
It's an EasyEDA (LCEDA) Pro project tarball including the schematic, the PCB, and the acrylic panel printing.   

Size: 100mm * 38mm * 6mm  
PCB: 1.6mm thickness, 4 Layers, JLC7628 (From JLCPCB; or anything similar)  
LF coil: find a 125kHz RFID coil with maximum 20mm diameter, ask the seller about its inductance, then calculate the value of resonance capacitors  
Battery: 302030 Li-Po Battery, 4.2V  
Top & Bottom acrylic panel: 1.0mm thickness, with rear adhesive (any type), routine light occlusion, glossy, printing on bottom  
Middle acrylic panel: 2.0mm thickness (with 302030 Li-Po battery), with rear adhesive (any type), routine light occlusion, glossy, printing on bottom  
(Note: I don't know if LCSC's panel printing service is avaliable outside mainland China, so I'll just list the details)  

![SCH_sch_hsr_pass_lite_v1p1_1-P1_2024-01-15](https://github.com/libc0607/hsr_nfc_pass_lite/assets/8705034/ecc3195b-1b22-4239-a31e-75d8ae69e006)  

## Disclaimer
There's no guarantee of its performance (actually, a bit worse -- due to the size of the coils), as it's only a toy designed for myself.  
Soldering the nRF52840's so-called "aQFN" package is f**king traumatic. Be calm.

## License 
Hardware (PCB, panel outline) design: GPL-3.0  

The picture on panel is from [Bilibili: 刃下狼血](https://space.bilibili.com/193006350), with a few changes.  
Since it's also a design from HoYoverse, it's better to ask them about the details on selling  
