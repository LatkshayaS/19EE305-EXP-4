# EX4 : HALFWAVE AND FULL WAVE RECTIFIERS
## AIM: 
To study the characteristics of half wave, full wave and bridge rectifier with and without filter and calculate the ripple factor, rectification efficiency and % regulation.

## COMPONENTS  AND  EQUIPMENT  REQUIRED: 
1.Diodes

2.Resistor

3.Transformer

4.Voltmeter

5.Ammeter

6.Breadboard 

7.CRO.

## THEORY: 
Rectifier changes ac to dc and it is an essential part of power supply. The unique property of a diode, permitting the current to flow in one direction, is utilised in rectifiers.

### Half Wave Rectifier:
Mains power supply is applied at the primary of the step-down transformer. All the positive half cycles of the stepped down ac supply pass through the diode and all the negative half cycles get eliminated. Peak value of the output voltage is less than the peak value of the input voltage by 0.6V because of the voltage drop across the diode.
For a half wave rectifier, Vrms = Vm/2 and Vdc = Vm/π: where Vrms = rms value of input, Vdc = Average value of input and Vm = peak value of output.


### Full Wave Rectifier:
During the positive half cycle of the transformer secondary voltage, diode is forward biased and is reverse biased. So a current flows through the diode     , load resistor and upper half of the transformer winding.During the  negative  half  cycle,diode becomes  forward  biased  and becomes reverse biased. The current then flows through the diode, load resistor and lower half of the transformer winding. Current flows through the load resistor in the same direction during both the half cycles. Peak value of the output voltage is less than the peak value of the input voltage by 0.6V because of the voltage drop across the diode.
During the positive half cycle of the secondary voltage, diodes and are forward biased and diodes and are reverse biased. Therefore, current flows through the secondary winding, diode , load resistor and diode. During the negative half cycle,and are forward biased and diodes and are reverse biased. Therefore, current flows through the secondary winding, diode . Load resistor During both the half cycles, the current flows through the load resistor in the same direction. Peak value of the output voltage is less than the peak value of the input voltage by 1.2V due to the voltage drop across two diodes. The ripple factor of the bridge rectifier is the same as that of full wave rectifier.
All rectifier outputs contain considerable amount of ripple in addition to the DC component. In order to avoid AC components, a filter is connected at the output of the rectifier.

Capacitor input filter, choke input filter, RC, CRC, LC, and CLC filters are the usually used filters. Capacitor input filter is the simplest and cheapest. A high value capacitor C is connected in shunt with the load resistor. Capacitor charges to peak voltage when the half cycle appears at the output. After the peak value is passed, the capacitor discharges through the load resistor slowly since the diode is reverse biased by the capacitor voltage. Before the capacitor voltage drops substantially, next output cycle arrives and the capacitor recharges to peak.

### Rectifier Efficiency:
Rectifier efficiency is defined as the ratio of DC output power to the input power from the AC supply. Even with ideal rectifiers with no losses, the efficiency is less than 100% because some of the output power is AC power rather than DC which manifests as ripple superimposed on the DC waveform.

## PROCEDURE:
1.   Wire up the half wave rectifier circuit without capacitor after testing all the components.
2.   Switch on the main supply. Observe the transformer secondary voltage waveform and output voltage waveform across the load resistor, simultaneously on the CRO screen. Note down  and calculate
3.   Connect the capacitor filter and observe the waveforms. Note down and calculate ripple factor, rectifier efficiency and %regulation using the expressions. Repeat for different capacitor values.
4.   Repeat the above steps for full wave and bridge rectifiers.

circuit diagram:

half wave rectifier with filter:
![half wave circuit](https://github.com/user-attachments/assets/29514cb3-a519-4761-a875-2d3a8d6459e3)

full wave rectifier with filter:

![full wave circuit](https://github.com/user-attachments/assets/acef3efb-b0dd-469c-a34c-37e846b942fd)

tabulation:

half wave rectifier with filter:

![half wave tabulation](https://github.com/user-attachments/assets/d02e425e-bf90-45e8-916b-dfb89c497f0f)


full wave rectifier with filter:

![full wave tabulation](https://github.com/user-attachments/assets/f57f2b84-4332-4cac-9830-b2fd4c9a4010)


waveform:

half wave rectifier with filter:

![half wave waveform](https://github.com/user-attachments/assets/e485545f-f0d7-48b7-8a0b-bb3dd88e5f10)

full wave rectifier with filter:

![waveform](https://github.com/user-attachments/assets/d49c4b77-6b9f-453a-920c-32b4583a7557)

## RESULT:
Input and Output waveforms of a half and full bridge-wave with /without filter are observed and plotted.
