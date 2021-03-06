# Transistor-Logic-with-LEDs
Building logic gates out of transistors, and validating them with LED's.<br>
These circuits might not appear as they conventionally do, when searching them up online. This is because of the added LED's in the circuits.<br>
<br>
<b>Note</b>: I didn't have any buttons or switches, so I used exposed wires to simulate the inputs.

## Resistor-Transistor Logic (RTL):
RTL refers to digital circuits built using resistors and bipolar junction transistors (BJTs).<br>
RTL is rarely used in modern digital circuits, but was used quite often in the past. A notable example is the [Apollo Guidance Computer](https://en.wikipedia.org/wiki/Apollo_Guidance_Computer), which used RTL integrated circuits. 

### NOT Gate:

<p align="center" style="vertical-align: top; position: relative">
<img align="top" src="https://github.com/rajatKumar2000/Transistor-Logic-with-LEDs/blob/master/Media/RTL_NOT_physical.gif"/>
</p>

<p align="center" style="vertical-align: top; position: relative">
<img align="top" src="https://github.com/rajatKumar2000/Transistor-Logic-with-LEDs/blob/master/Media/RTL_NOT_falstad.gif"/>
</p>

[Simulated circuit of the NOT gate](https://www.falstad.com/circuit/circuitjs.html?cct=$+1+0.000005+10.20027730826997+52+5+50%0At+256+192+304+192+0+1+0.5625838956636969+0.6662815013523128+100%0Ag+0+336+0+368+0%0Ar+304+48+304+112+0+330%0Ar+176+192+240+192+0+10000%0As+144+48+144+128+0+0+false%0Aw+240+192+256+192+0%0Aw+304+112+304+176+0%0A162+448+112+448+224+2+default-led+1+0+0+0.01%0Aw+304+112+448+112+0%0Av+0+336+0+224+0+0+40+5+0+0+0.5%0Aw+0+224+0+48+0%0Aw+0+48+144+48+0%0Aw+144+48+304+48+0%0Aw+304+208+304+336+0%0Aw+448+224+448+336+0%0Aw+448+336+304+336+0%0Aw+304+336+144+336+0%0Ar+144+192+144+240+0+330%0A162+144+240+144+288+2+default-led+1+0+0+0.01%0Aw+144+128+144+192+0%0Aw+144+192+176+192+0%0Aw+144+288+144+336+0%0Aw+144+336+0+336+0%0A)

### AND Gate:

<p align="center" style="vertical-align: top; position: relative">
<img align="top" src="https://github.com/rajatKumar2000/Transistor-Logic-with-LEDs/blob/master/Media/RTL_AND_physical.gif"/>
</p>

<p align="center" style="vertical-align: top; position: relative">
<img align="top" src="https://github.com/rajatKumar2000/Transistor-Logic-with-LEDs/blob/master/Media/RTL_AND_falstad.gif"/>
</p>

[Simulated circuit of the AND gate](https://www.falstad.com/circuit/circuitjs.html?cct=$+1+0.000005+10.20027730826997+52+5+50%0Ag+368+512+368+528+0%0At+320+240+368+240+0+1+0.5666342366950331+0.654819748353891+100%0Ar+368+128+368+64+0+330%0At+320+272+368+272+0+1+0.5669831991589425+0.6559324256645581+100%0Aw+368+288+368+512+0%0Ar+272+240+192+240+0+10000%0Ar+240+272+320+272+0+10000%0A162+368+128+368+224+2+default-led+1+0+0+0.01%0Av+96+368+96+288+0+0+40+5+0+0+0.5%0Aw+96+64+368+64+0%0Aw+96+368+96+432+0%0Aw+240+512+368+512+0%0As+128+240+160+240+0+0+false%0A162+240+416+240+464+2+default-led+1+0+0+0.01%0Aw+320+240+272+240+0%0Ar+240+416+240+352+0+330%0Aw+240+352+240+272+0%0Ar+192+416+192+352+0+330%0A162+192+416+192+464+2+default-led+1+0+0+0.01%0Aw+192+352+192+240+0%0Aw+240+464+240+512+0%0Aw+240+512+192+512+0%0Aw+192+464+192+512+0%0Aw+192+512+96+512+0%0Aw+96+432+96+512+0%0Aw+160+240+192+240+0%0As+128+272+160+272+0+0+false%0Aw+160+272+240+272+0%0Aw+96+288+96+272+0%0Aw+96+272+128+272+0%0Aw+96+272+96+240+0%0Aw+96+240+128+240+0%0Aw+96+240+96+64+0%0A)

### OR Gate:

<p align="center" style="vertical-align: top; position: relative">
<img align="top" src="https://github.com/rajatKumar2000/Transistor-Logic-with-LEDs/blob/master/Media/RTL_OR_physical.gif"/>
</p>

<p align="center" style="vertical-align: top; position: relative">
<img align="top" src="https://github.com/rajatKumar2000/Transistor-Logic-with-LEDs/blob/master/Media/RTL_OR_falstad.gif"/>
</p>

[Simulated circuit of the OR gate](https://www.falstad.com/circuit/circuitjs.html?cct=$+1+0.000005+10.20027730826997+52+5+50%0Ag+96+512+96+528+0%0At+400+272+432+272+0+1+0.5705822351970268+0.6398227218979092+100%0Ar+352+272+400+272+0+10000%0Av+96+368+96+288+0+0+40+5+0+0+0.5%0A162+352+336+352+384+2+default-led+1+0+0+0.01%0Ar+352+336+352+272+0+330%0Ar+192+336+192+272+0+330%0A162+192+336+192+384+2+default-led+1+0+0+0.01%0Aw+96+368+96+512+0%0Ar+192+272+240+272+0+10000%0At+240+272+272+272+0+1+0.5705822351970268+0.6398227218979092+100%0Aw+432+240+432+256+0%0A162+432+160+432+208+2+default-led+1+0+0+0.01%0Ar+432+160+432+64+0+330%0Aw+96+64+432+64+0%0As+192+128+192+176+0+0+false%0Aw+192+224+192+272+0%0Aw+352+224+352+272+0%0As+352+128+352+176+0+0+false%0Aw+96+288+96+128+0%0Aw+192+384+192+512+0%0Aw+352+512+432+512+0%0Aw+432+288+432+512+0%0Aw+432+240+432+208+0%0Aw+352+384+352+512+0%0Aw+272+208+272+256+0%0Aw+272+288+272+512+0%0Aw+272+208+432+208+0%0Aw+352+128+192+128+0%0Aw+192+512+272+512+0%0Aw+272+512+352+512+0%0Aw+192+512+96+512+0%0Aw+96+128+192+128+0%0Aw+192+176+192+224+0%0Aw+352+176+352+224+0%0Aw+96+128+96+64+0%0A)

## Diode-Transistor Logic (DTL):
DTL circuits use diodes to perform the logical operations of the intended logic gate. The transistors are used as inverting amplifiers.<br>
DTL was a slight improvement over RTL circuits due to its greater [fan-out](https://en.wikipedia.org/wiki/Fan-out) capabilities.

### NOT Gate:

<p align="center" style="vertical-align: top; position: relative">
<img align="top" src="https://github.com/rajatKumar2000/Transistor-Logic-with-LEDs/blob/master/Media/DTL_NOT_physical.gif"/>
</p>

<p align="center" style="vertical-align: top; position: relative">
<img align="top" src="https://github.com/rajatKumar2000/Transistor-Logic-with-LEDs/blob/master/Media/DTL_NOT_falstad.gif"/>
</p>

[Simulated circuit of the NOT gate](https://www.falstad.com/circuit/circuitjs.html?cct=$+1+0.000005+10.20027730826997+54+5+50%0Ag+336+272+336+320+0%0Ar+240+176+240+96+0+4700%0Ar+336+96+336+176+0+1000%0Aw+336+176+336+240+0%0Aw+240+96+336+96+0%0At+288+256+336+256+0+1+-1.2376823587603747+0.4400315265762501+100%0Ad+240+256+288+256+2+default%0Ad+240+256+192+256+2+default%0AL+160+256+96+256+0+0+false+5+0%0AR+240+96+144+96+0+0+40+5+0+0+0.5%0Aw+240+176+240+224+0%0Aw+240+224+240+256+0%0A162+336+176+416+176+2+default-led+1+0+0+0.01%0Ag+416+176+416+224+0%0Ag+160+336+160+352+0%0A162+160+288+160+336+2+default-led+1+0+0+0.01%0Ar+160+256+160+288+0+1000%0Aw+160+256+192+256+0%0A)
<br>
<br>
In the simulated circuit gif, the input is described as either L (0V) or H (5V). So when building this on my breadboard, I had to use two exposed wires to simulate the inputs.
When the input node is being touched by the red wire (VCC), then the input is 5V. When it is being touched by the orange wire (ground), then the input is 0V.
<br>
<br>
A common misconception would be to think that not having anything touching the input node, would result in 0V, but this is false.
The voltage difference between the input node and ground would be around 1V, this is a result of how the other components are reacting in the circuit. 
<br>
<br>
So, when VCC or ground is not touching the input node, we can say that there is no logical 0 or 1 input, thus the output is not logical either.

## Transistor-Transistor Logic (TTL):
TTL circuits use transistors to perform both the logical operations and the amplification function.<br>
In comparasion to RTL and DTL, TTL circuits were a massive improvement in speed and power consumption.

### NOT Gate:

<p align="center" style="vertical-align: top; position: relative">
<img align="top" src="https://github.com/rajatKumar2000/Transistor-Logic-with-LEDs/blob/master/Media/TTL_NOT_physical.gif"/>
</p>

<p align="center" style="vertical-align: top; position: relative">
<img align="top" src="https://github.com/rajatKumar2000/Transistor-Logic-with-LEDs/blob/master/Media/TTL_NOT_falstad.gif"/>
</p>

[Simulated circuit of the NOT gate](https://www.falstad.com/circuit/circuitjs.html?cct=$+1+0.000005+10.20027730826997+54+5+50%0AR+192+112+112+112+0+0+40+5+0+0+0.5%0Ar+352+112+352+192+0+1000%0Aw+352+192+352+224+0%0At+192+192+192+240+0+1+0.5897979461877102+-3.7608606662210837+100%0At+288+240+352+240+0+1+0.6064001768814519+0.6493413875912059+100%0Aw+208+240+288+240+0%0AL+128+240+80+240+0+1+false+5+0%0Ag+352+256+352+336+0%0Aw+192+112+352+112+0%0Ar+192+112+192+192+0+4700%0A162+352+192+448+192+2+default-led+1+0+0+0.01%0Ag+448+192+448+240+0%0A162+128+288+128+320+2+default-led+1+0+0+0.01%0Ar+128+240+128+288+0+1000%0Aw+128+240+176+240+0%0Ag+128+320+128+336+0%0A)
<br>
<br>
Similar to my DTL NOT gate circuit, I had to use two exposed wires to simulate the logical 0 and 1 input.
