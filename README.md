# X-B120W-4-LITE - SIMPLE MAIN-CIRCUIT MODULE OF 120 WATTS CLASS-B AUDIO POWER AMPLIFIER MAIN-CIRCUIT FOR 4-OHMS OUTPUT LOAD

This is a main-circuit model of power amplifier applies a non-symmetrical VAS with active-load. This model is designed to be quit simple as possible, in which the simplicity is about to achieve the optimal work speed of this power amp model.

![X-B120W-4 schematic diagram](https://github.com/X-ANONYMOUS-POWER-AMPLIFIER/X-B120W-4-LITE/blob/main/X-B120W-4-LITE-120W-CLASS-B-POWER-AMP-SIMPLE-MAIN-CIRCUIT.png?raw=true)

This circuit is designed to fit with a small circuit board, and intentionally designed for a single-sided circuit board, so as you see that it has some wire-jumpers. A KISS principle is applied with it. (KISS: Keep It Simple-Stupid.)

As you also see, this model isn't completed with the current-limiters within its output-stage, that you're probably questioning it, why? It is, as such current-limiter won't be working effectively, and therefore not applied within this model. It will better a special output protector circuit in a different circuit board applied to take function for protecting this power amp's output-stage.

## Advanced VAS Model

The VAS of this power amp model has an active load that synchronized with the main VAS side to be working as well a fully symmetrical VAS. The output signal from the LTP buffer (Q4006's emitter) copied by a grounded-base amplifier or signal-current-buffer, Q4008, to supply a copy of signal to make the VAS's loader, Q4009, to be fully activelly working side-by-side with the main VAS, Q4007. 

The amplification workflow between LTP buffer, Q4006, into the VAS loader, Q4009, isn't for tackling the DC amplification, but limited for tackling AC amplification, to prevent DC offset. The LTP buffer output, Q4006's emitter, is coupled by C4007 into the emitter of Q4008. to gain AC signal only, thus Q4008 can keep its main function as a current-souce to provide a constant forward-bias-current for Q4009's base.

![Circuit board preview 1](https://github.com/X-ANONYMOUS-POWER-AMPLIFIER/X-B120W-4-LITE/blob/main/PCB-PREVIEW/1.png)
![Circuit board preview 2](https://github.com/X-ANONYMOUS-POWER-AMPLIFIER/X-B120W-4-LITE/blob/main/PCB-PREVIEW/2.png)
![Circuit board preview 3](https://github.com/X-ANONYMOUS-POWER-AMPLIFIER/X-B120W-4-LITE/blob/main/PCB-PREVIEW/3.png)
![Circuit board preview 4](https://github.com/X-ANONYMOUS-POWER-AMPLIFIER/X-B120W-4-LITE/blob/main/PCB-PREVIEW/4.png)
![Circuit board preview 5](https://github.com/X-ANONYMOUS-POWER-AMPLIFIER/X-B120W-4-LITE/blob/main/PCB-PREVIEW/5.png)

## License

1. **License Grant**  
The Licensor hereby grants you a worldwide, royalty-free, non-exclusive, perpetual license to use the circuit design for the non-commercial purposes only.
2. **Conditions**  
Attribution: You must provide credit to the original creator when distributing this circuit design.
3. **Disclaimer of Warranty**  
THE DESIGN IS PROVIDED "AS IS". THE LICENSOR MAKES NO WARRANTIES, EXPRESS OR IMPLIED, REGARDING THE DESIGN, INCLUDING BUT NOT LIMITED TO ANY IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.
4. **Limitation of Liability**  
IN NO EVENT SHALL THE LICENSOR BE LIABLE FOR ANY DAMAGES, INCLUDING BUT NOT LIMITED TO DIRECT, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OF THE DESIGN.

Design files bundle is available for download by follow the URL: [https://github.com/X-ANONYMOUS-POWER-AMPLIFIER/X-B120W-4-LITE/archive/refs/heads/main.zip](https://github.com/X-ANONYMOUS-POWER-AMPLIFIER/X-B120W-4-LITE/archive/refs/heads/main.zip)

