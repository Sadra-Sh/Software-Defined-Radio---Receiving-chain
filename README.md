# Software Defined Radio (SDR) Project

## Introduction
This project focuses on the development of the receiving chain of a Software Defined Radio (SDR). The receiving end is responsible for receiving radio frequency signals picked up by the antenna and preparing them for further processing. This README provides an overview of the PCB design for the receiving chain of the SDR.

## Receiving Chain Overview
The receiving chain of the SDR consists of several key components that work together to process incoming signals:

1. **Bandpass Filter**: A bandpass filter is used to select a specific range of frequencies (8-16 MHz) from the incoming signals, filtering out unwanted frequencies.

2. **Voltage Limiter**: The voltage limiter limits the amplitude of the signals to prevent extraneous amplitudes from damaging sensitive components downstream.

3. **Mixer**: A Gilbert Cell mixer is used in the design to down-convert the RF signals to a lower frequency range. Additionally, an IC diode ring mixer is implemented as a fail-safe mechanism.

4. **Low Pass Filter**: The low pass filter further reduces the frequency of the signals, preparing them for demodulation.

5. **Amplifier**: An amplifier is used to bring the signals up to a level that can be easily demodulated and further processed.

## PCB Design
The PCB design for the receiving chain of the SDR was carefully crafted to ensure optimal performance and reliability. Key considerations included signal integrity, power distribution, and component placement.

## Team Contributions
- **Sadra**: Responsible for the Gilbert Cell Mixer design, and the fail safe mixer IC. Component placement and routing of the mixers, as well as board manufacturing and testing.
- **Saleh**: Responsible for the Bandpass filter and voltage limtier, component placement and routing, and board manufacturing and testing. 
- **Junyi**: Responsible for the Lowpass filter and Amplifier, component placement and routing, board testing and layout verification.

## Project Status
The final PCB is currently being manufactued. Components are being soldered onto the board and getting ready for testing. Future updates and improvements may included on this README file.

## Resources
- [Link to GitHub Repository](https://github.com/Sadra-Sh/Software-Defined-Radio---Receiving-chain)
- [Additional Documentation](https://www.linkedin.com/in/sadra-shirdarreh/)

## Contact
For questions or inquiries about the project, please contact me at sadra.shirdarreh@mail.utoronto.ca.

## Images
**REV 1.0**  
<img width="745" alt="image" src="https://github.com/Sadra-Sh/Software-Defined-Radio---Receiving-chain/assets/143111135/1d101c16-9ef2-4aa0-9494-b22bc404066f">

**REV 2.0** 
<img width="973" alt="image" src="https://github.com/Sadra-Sh/Software-Defined-Radio---Receiving-chain/assets/143111135/3cc07a7c-5ce3-453b-a26d-b86171e368a6">

**Final Schematic**
<img width="953" alt="image" src="https://github.com/Sadra-Sh/Software-Defined-Radio---Receiving-chain/assets/143111135/6db08808-1e55-4984-a861-44bc8379abc9">
<img width="1022" alt="image" src="https://github.com/Sadra-Sh/Software-Defined-Radio---Receiving-chain/assets/143111135/f6d1f7c3-ae4a-4290-956d-c08f747544f2">
<img width="709" alt="image" src="https://github.com/Sadra-Sh/Software-Defined-Radio---Receiving-chain/assets/143111135/cd9291cd-f1ef-4c18-a766-3a93ddf59253">
<img width="831" alt="image" src="https://github.com/Sadra-Sh/Software-Defined-Radio---Receiving-chain/assets/143111135/ba99bc4e-000d-42bf-9e6a-d7c0402c5dda">
<img width="823" alt="image" src="https://github.com/Sadra-Sh/Software-Defined-Radio---Receiving-chain/assets/143111135/6f69947c-d871-4904-8954-9f1e323db148">






