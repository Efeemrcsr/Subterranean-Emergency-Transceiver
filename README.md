# Integrated Circuits Engineering Challenge: Subterranean Transceiver

## Overview
This repository contains circuit designs and simulations developed for an Integrated Circuits (IC) Engineering Challenge. The project focuses on designing discrete analog and RF stages for a subterranean emergency transceiver system, modeled and verified using LTspice.

## Circuit Modules
The challenge is broken down into specific functional blocks, each designed and simulated independently before final integration:
* **Low-Noise Analog Baseband (`Low-Noise Analog Baseband.asc`):** Signal conditioning and amplification with minimal noise figure.
* **TTE Low-Frequency Transmitter (`TTE Low-Frequency Transmitter.asc`):** Specialized transmitter designed for Through-Earth (TTE) signal propagation.
* **VHF Airband Receiver (`VHF Airband Receiver.asc`):** RF receiver stage tuned for airband emergency communication.
* **Automated Seismic Warning (`Automated Seismic Warning.asc`):** Analog detection loop for seismic activity alerts.
* **Final Integration (`Final.asc`):** The complete, integrated transceiver circuit combining all subsystems.

## Tools & Technologies
* **LTspice:** Schematic capture, transient analysis, and AC sweep simulations.
* **Analog/RF IC Design Principles:** Op-Amps, BJT/MOSFET transistor sizing, passive RLC filtering, and noise optimization.
