# DC-DC-Buck-Boost-Converter
Buck–Boost DC-DC converter using TL494 PWM controller with MATLAB simulation and hardware implementation.

## Specifications

| Parameter | Value |
|---|---|
| Input Voltage | 15 V |
| Output Voltage | 12–18 V |
| Output Current | 1 A |
| Switching Frequency | 12.5 kHz |

## Buck–Boost Converter

A Buck–Boost converter is a DC-DC converter capable of operating in both step-up and step-down modes by controlling the PWM duty cycle.

### Working Principle

- During the ON state, the inductor stores energy from the input supply.
- During the OFF state, the stored energy is transferred to the load through the diode.
- The output voltage is regulated by varying the PWM duty cycle.

## Converter Equation

```math
V_o = -\frac{D}{1-D}V_{in}
```

## Hardware Implementation

- Breadboard testing for initial verification
- Final soldered implementation on perfboard
- MATLAB/Simulink based simulation and waveform analysis

## Observed Waveforms

- PWM gate pulses
- Diode current
- Inductor voltage
- Inductor current 

## Tools Used

- MATLAB/Simulink
- Oscilloscope
- TL494 Driver Board
- Perfboard Prototyping

## Skills Demonstrated

- Power Electronics
- PWM Control
- DC-DC Converter Design
- Hardware Prototyping
- MATLAB Simulation
