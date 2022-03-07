# Instrumentation-Amplifier-for-ECG-System-Application
- [Abstract](#abstract)
- [Reference Circuit Diagram](#reference-circuit-diagram)
- [Circuit Details](#circuit-details)
- [Software Used](#software-used)
    * [eSim](#esim)
    * [NgSpice](#ngspice)
    * [Makerchip](#makerchip)
- [Circuit Diagram in eSim](#circuit-diagram-in-esim)
- [Waveforms](#waveforms)
    * [Input(v1)](#input(v1))
    * [Input(v2)](#input(v2))
    * [Output of instrumentation amplifier](#Output-of-instrumentation-amplifier)
    *  [Output waveform](#Output-waveform)
   
    
- [Acknowlegdements](#acknowlegdements)
- [References](#references)


## Abstract
An instrumentation amplifier is a type of integrated circuit (IC) that is primarily used for signal amplification. The signal energy at the input to the instrumentation amplifiers will be extremely low. As a result, the instrumentation amplifier needs to be precise and have a high gain with a single control, the gain should be easily adjustable. Because common mode signals like as noise are commonly present in transducer output when transmitted over long lines, the instrumentation
amplifier should have a high CMRR. It must also have a high slew rate in order to accommodate rapid event rise times and offer the most not distorted output voltage swing possible. To avoid loading, it must have both a high input and a low output impedance.

## Reference Circuit Diagram
![circuit](https://user-images.githubusercontent.com/100235259/157100627-ee1e69b2-949e-40b9-909d-6d1bfde5adfa.png)

## Circuit Details
An Electrocardiogram or ECG is an instrument that is used
to monitor the electrical activity of a heartbeat. It takes
measurements and examines the flow of electricity from each
heartbeat. ECG measurements are taken by attaching leads to
the skin of the patient because of the physical constraints of
monitoring the heart through the surface of the skin, detectable signal is incredibly small and electrical noise can
be relatively large this means the real world ECG
instruments use amplifiers and filters to condition the signal
amplifiers, Amplifiers converts energy from a power source
to increase the amplitude of an input signal. A common way
to rate this magnification is the ratio of voltage measured at
the output port to voltage measured at the input port this ratio
is typically refer to as gain. There are many type of
amplifiers like inverting amplifier, non-inverting amplifier
amplifier, differential amplifier, instrumentation amplifier
etc. Here we are using Instrumentation amplifier, it combines
properties like DC offset, very high input impedance and
high common mode rejection which is the rejection of
unwanted input signal common to both input leads. Often
with instrumentation amplifiers they are constructed so that
all the resisters have the same value except for Rgain, then
Rgain is adjusted to change the properties of the amplifiers. Instrumentation amplifiers have the benefit that they don’t
draw current from sources being measured.

## Software Used
### eSim
It is an Open Source EDA developed by FOSSEE, IIT Bombay. It is used for electronic circuit simulation. It is made by the combination of two software namely NgSpice and KiCAD.
</br>
For more details refer:
</br>
https://esim.fossee.in/home
### NgSpice
It is an Open Source Software for Spice Simulations. For more details refer:
</br>
http://ngspice.sourceforge.net/docs.html
### Makerchip
It is an Online Web Browser IDE for Verilog/System-verilog/TL-Verilog Simulation. Refer
</br> https://www.makerchip.com/
### Verilator
It is a tool which converts Verilog code to C++ objects. Refer:
https://www.veripool.org/verilator/

## Circuit Diagram in eSim
![Final_ckt](https://user-images.githubusercontent.com/100235259/157101943-f156ef70-877e-4498-ac0e-3bbbd83adfc6.PNG)

## Waveforms
### input(v1)
![1e](https://user-images.githubusercontent.com/100235259/157104919-fec3a4b0-6351-4ea4-ae20-3b06053c5a0a.PNG)

### input(v2)


![2e](https://user-images.githubusercontent.com/100235259/157104968-702e4667-c762-4d53-8258-8f33a9184df7.PNG)
### Output of instrumentation amplifier
![3re](https://user-images.githubusercontent.com/100235259/157105291-d28960c9-0003-4bbd-a284-edf966c6d947.PNG)
### Output waveform
![4e](https://user-images.githubusercontent.com/100235259/157105475-b33f0393-aa6b-404f-8dcb-bd124feace7e.PNG)


## Acknowlegdements
1. FOSSEE, IIT Bombay
2. Steve Hoover, Founder, Redwood EDA
3. Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd. - kunalpghosh@gmail.com
4. Sumanto Kar, eSim Team, FOSSEE
## References
[1] Xiu, Limei, and Zheying Li. "Low-powerinstrumentation amplifier IC design for ECGsystemapplications." Procedia Engineering 29 (2012): 1533-1538
[2]Kaewfoongrungsie, Piroon, Nipon Theera-Umpon, and Sansanee Auephanwiriyakul. "ECG Holter Recorder Via Mobile Phone." Proceedings of the 3rd International Symposium on Biomedical Engineering, Grand Mercure Fortune Bangkok, Thailand (ISBME 2008). 2008.

