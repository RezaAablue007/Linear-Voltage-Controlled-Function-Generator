# Design and Verification of a Voltage-Controlled Function Generator

## Abstract
This report presents the design and verification process of a Voltage-Controlled Function Generator (VCFG) used in electronic music synthesis, data encoding, and automatic control and measurement. The VCFG generates frequency based on an external control signal, and its output frequency is determined by the relationship 𝑓𝑜 = 𝑘 × 𝑉𝐶, where 𝑘 is the proportionality constant in Hz/Volt. The design project focuses on creating symmetrical square-wave and triangular waveforms with a Total Harmonic Distortion of less than 1% for the triangular waveforms.

## Objectives
The main objectives of the design project are to design a VCFG with the following specifications:
- Output frequency: Two frequency ranges of approximately 100 Hz to 3100 Hz (range #1) and 20 Hz to 620 Hz (range #2) with control voltage 𝑉𝐶 varying from 0.1 to 5 Volts D.C.
- Output waveform: User-selectable triangular or square-wave with 0 to 4 volts peak amplitude (controlled by a potentiometer).
- Power supplies: +/- 10 Volts D.C.

## Introduction
The Voltage-Controlled Function Generator must meet all design specifications with little to no error. The project is divided into five milestones, each verifying a component of the final design. Milestone 1 involves designing a fixed-frequency waveform generator using an inverting integrator and a noninverting bistable comparator. Milestone 2 adds a DC-to-(+/-) DC converter and a limiter circuit to stabilize the output waveform. Milestone 3 combines the DC converter and waveform generator for testing. Milestone 4 implements frequency range and amplitude control using switches and potentiometers.

## Design Components
The VCFG design involves the following key components:
- DC-to-(+/-) DC Converter: Converts D.C voltage to a square wave signal with threshold voltages determining the output waveform.
- Inverting Integrator: Utilizes an input resistor and capacitor in the feedback path to create time-dependent output voltage changes.
- Bistable Comparator: Provides hysteresis to prevent noise and distortion at threshold voltage levels.
- Gain Control Circuit: Uses potentiometers to control the amplitude of the output voltage.

## Conclusion
The design project successfully achieved the desired output frequency and waveform requirements using five OP-AMPs, a Bipolar Junction Transistor, Zener diodes, resistors, and capacitors. The voltage-controlled function generator can operate in two frequency ranges and produce waveforms with a peak amplitude of around 4 volts. Minor deviations between simulation and design analysis exist, but they do not significantly impact the overall functionality of the VCFG. Implementing the design on real-life lab hardware is recommended for further testing and verification. Overall, the project was successful and provided valuable learning experiences.
