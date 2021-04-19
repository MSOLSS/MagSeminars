---
title: An Experimentalist’s Approach to Solid State Detectors
author: Nithin Sivadas
layout: post
---

A solid-state charged particle detector converts the particle's kinetic energy into electric charge and is subsequently read out as a current or voltage signal. Within the detector's operating range, the signal's charge is proportional to the particle's energy deposited, which is the core fact that allows us to use these instruments to measure the energy and type of the incident particles reliably. Dr. Greeley gives us a background of the basic structure and physics of solid-state detectors and electronics that converts the electric charge into the number, energy, and type of the incident particle.

Dr. Greeley points out that most solid-state detectors are made of semiconductors such as silicon and germanium, and they operate as voltage-biased p-n junction diodes. And using a stack of them allows one to observe a wide range of energies due to the increased length of active material (i.e., the semiconductor). It allows discrimination between particle types since the rate of energy deposition is different for particles with different atomic numbers of particular incident energy. Commonly, each detector stack is attached to an analog electronics chain to convert the charge from the semiconductor to a shaped voltage pulse (using a charge-sensitive pre-amplifier and pulse shaper). The analog chain can mitigate the voltage pulse pile-up corresponding to consecutively incident particles and improve the shortest response time between two incident particles (dead time) of the detector. These analog signals are then digitized using an analog to digital converter (ADC) system, stored for further processing and compression, and relayed to spacecraft communication systems.

Dr. Greeley uses two new silicon-based detectors that she has worked on, MERIT and AGILE, as examples for explaining the steps that go into developing charged particle detectors. After the overview of the electronics design, she discusses simulating the interaction of charged particles with the substrates that make up the detector. For this, Dr. Greeley uses GEANT4 - a robust Monte Carlo code that tracks the energy deposited by energetic particles in matter. She then details one of the critical steps of detector development - calibration of the input particle energy and the digital output. She discussed three common methods of calibration:

1. Using known radioactive source emissions as input to the detector substrate
2. Using charge pulse generators as input to the analog electronics
3. Testing the whole detector chain using naturally present cosmic muons

During her talk, she also mentions the importance of shielding the active detector material from radiation contributing to the noise, by limiting side penetrators such as aluminum or tungsten layers.

Before concluding her talk, Dr. Greeley also discussed the novel technique of pulse shape discrimination as an alternate method to differentiate between particle types. This technique uses the variations in the semiconductor current (and therefore the rise times of the output voltage pulse) for different particle species and energy. She demonstrates this technique's usefulness, using more detailed simulations developed for the AGILE instrument using GEANT4, Weightfield2, and LTspice.

Dr. Greeley suggests the following book for additional and detailed reading on solid-state detectors: 

[Semiconductor Detector Systems, by  Helmuth Spieler][1] 

You can find the recording of Dr. Greeley's seminar on our [YouTube Channel][2].

[1]: https://www.ph.unimelb.edu.au/~djpeake/Spieler_Semiconductor_Detector_Systems.pdf
[2]: https://www.youtube.com/watch?v=t7mymenxwtA
