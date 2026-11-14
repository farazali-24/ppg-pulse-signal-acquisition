
# PPG Pulse Signal Acquisition

## Project Overview

This project focuses on the construction and testing of an analogue photoplethysmography (PPG) circuit to acquire a pulse waveform using a pulse oximeter probe.

The circuit uses red and infrared light from the probe, a photodiode and analogue signal-conditioning circuitry to detect variations in light absorption caused by pulsatile blood flow. The acquired signal was observed and tested using an oscilloscope.

The project involved LED driver testing, breadboard prototyping, circuit layout planning, PCB assembly and experimental signal measurement.

## Demonstration

### PPG Waveform — Oscilloscope

<img src="docs/ppg-oscilloscope-waveform.jpeg" width="600" alt="PPG pulse waveform displayed on a Tektronix oscilloscope">

### Live PPG Signal

<img src="docs/ppg-oscilloscope-live.gif" width="600" alt="Animated oscilloscope recording showing the PPG pulse signal">

## Hardware

- Pulse oximeter probe with red and infrared LEDs and photodiode
- MCP6292 operational amplifier
- MOSFETs for LED control
- Resistors, capacitors and adjustable trimmer resistor
- Breadboard and prototype PCB
- 3.3 V supply
- Tektronix digital oscilloscope

## How It Works

1. An LED inside the pulse oximeter probe illuminates the fingertip.
2. The photodiode detects transmitted light, which varies with the arterial pulse.
3. A transimpedance amplifier converts the photodiode current into a voltage signal.
4. Analogue signal conditioning helps isolate and amplify the pulsatile component.
5. The resulting PPG waveform is observed on the oscilloscope.

## Circuit Construction

The LED driver was initially tested using red and green indicator LEDs before the pulse oximeter probe was connected.

The analogue circuit was assembled and tested on a breadboard. A component layout was prepared to support transferring the circuit onto a prototype PCB.

<img src="docs/ppg-breadboard-prototype.jpeg" width="500" alt="PPG analogue circuit assembled on a breadboard">

<img src="docs/ppg-pcb-implementation.jpeg" width="500" alt="PPG circuit assembled on the prototype PCB">

## Results

Oscilloscope testing produced a visible, repeating PPG waveform with identifiable pulse peaks. The photograph and animated recording provide evidence of signal acquisition and practical testing.

## Documentation

Detailed circuit construction photographs, LED driver tests, layout images, the editable Fritzing file and oscilloscope evidence are available in the [project documentation](docs/README.md).

## Skills Demonstrated

- Analogue circuit prototyping
- LED driver circuit testing
- Photodiode signal acquisition
- Operational amplifier signal conditioning
- PCB assembly and wiring
- Oscilloscope measurement and testing
- Technical documentation
  
