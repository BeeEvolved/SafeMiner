
<p align="center">
  <img src="https://github.com/BeeEvolved/SafeMiner/blob/main/images/SafeMinerLogoSmall.png" alt="SafeMinerLogo">
</p>


# SafeMiner
SafeMiner is a hardware design aimed at creating a safety system for Bitcoin mining hardware. The Design incorporates fire detection and automatic shutdown to ensure the safety of miners and mining operations.  Including home miners that often mine from home or a garage. Protecting personal property, yourself, and your family.
<p align="center">
  <img src="https://github.com/BeeEvolved/SafeMiner/blob/main/images/SafeMinerImage1%20(2).jpg" alt="SafeMinerLogo">
</p>

### Early detection and prevention
The primary goal is to detect an event at the spark, arc, thermal spike or smoke phase before it can become true blazing fire. It’s obviously going to be a case-by-case scenario, but cutting the power certainly could prevent unpleasant outcomes. The wording of “fire detection” of the SafeMiner might be a little confusing for some, but the overall mission is to detect the earliest catalyst of a fire, sudden thermal spike, sparks, or arcs on a hashboard or Bitcoin miner to mitigate losses or damage.

### SafeMiner hardware  Design

SafeMiner is a hardware design project aims at creating a safety system for Bitcoin mining hardware. The design incorporates fire detection and an automatic shutdown mechanism to ensure the safety of miners and mining operations.

## Future SafeMiner designs 
Currently, the flagship design is tailored for the QuadAxe configuration, housing four Bitaxes within an S9 chassis. Following extensive testing, future designs will be adapted to popular Bitcoin miners such as the Antminer S19, S21 and T21.

## Overview

This repository contains the hardware designs of the SafeMiner project. The design implements various safety features, including automatic shutdown, to protect Bitcoin mining operations from fire.

## Fire Sensor and Automatic shutdown Operation Explanation
### Fire Detection and Safety Mechanism

- **Q1 (Flame Sensor):** This component detects fires near the mining hardware, hashboard or inside chassis. When activated, its signal pin connects to the gate pin of the MOSFET.
- **Gate (MOSFET - IRLZ44NPBF):** The MOSFET controls power distribution to the mining hardware. Its gate pin receives the signal from the flame sensor. When a fire is detected, the MOSFET shuts off power to the connected hardware, preventing potential hazards.

## BOM Component Part Numbers

The following components are used in the SafeMiner PCB design:

- **C1:** 10uF capacitor (Digi-Key: 1189-2294-ND)
- **R1:** 5K resistor (Digi-Key: MFP25SBBE52-5K-ND)
- **R2:** 33K resistor (Digi-Key: 13-CFR-25JR-52-33KCT-ND)
- **D1:** 1N4007 diode (Digi-Key: 1N4007GDICT-ND)
- **Gate (MOSFET):** IRLZ44NPBF (Digi-Key: IRLZ44NPBF-ND)
- **Q1:** Flame sensor (Digi-Key: 399-USEQFCSA455100-ND)
- **RV1:** 5K trimmer potentiometer (Digi-Key: 3362P-502LF-ND)
- **J1:** Terminal blocks (Digi-Key: A113320-ND)

## Disclaimer

**Important Note:** This PCB design is currently untested and NOT ready for usage without proper testing. We strongly advise against attempting to use or manufacture the design until it has been thoroughly tested and validated for reliability and safety.

We are currently in the process of ordering PCBs/parts and will conduct extensive testing upon their arrival. The results of our testing will be published to this repository, providing transparency and ensuring the design's suitability for production use.

Thank you for your understanding and patience as we work to ensure the safety and reliability of these designs.

## Support this project?

It's always appreciated to receive support for purchasing PCB boards and prototype parts. If you'd like to contribute to this project and help accelerate the effort, you can do so via Bitcoin: 1P6gz8bggna5s93th9CxNommxcNivN2bPp or  GitHub Sponsorship


