# Ideal Six-Port Interferometer

## Overview

Design and analysis of a six-port interferometer using ideal 90° hybrid couplers.

## Objective

The objective of this stage was to design the six-port circuit using ideal 90° hybrid couplers and evaluate its RF performance through simulation.

## Design

The six-port circuit was designed using ideal 90° hybrid coupler blocks along with a Wilkinson Power Divider for initial power splitting.

## Analysis

The following parameters were analyzed:

* S-parameters
* Magnitude response
* Phase response
* Power division
* Port isolation

## Simulation Setup

The six-port microwave network was simulated in Keysight ADS using S-parameter analysis over the frequency range of **0.5 GHz to 5 GHz**.

## Simulation Observations

* The simulated output ports exhibit an insertion loss of approximately **−6 dB**.
* The input signal is initially divided equally by the **Wilkinson Power Divider**, producing an approximately **−3 dB** power split.
* The signals are then further distributed through the **90° Hybrid Couplers**, resulting in an additional approximately **−3 dB** division.
* Consequently, each output port receives approximately one-quarter of the input power, corresponding to an overall insertion loss of approximately **−6 dB**.
* The output responses remain nearly identical throughout the frequency sweep, demonstrating balanced power distribution and consistent operation of the six-port network.
* The phase responses vary continuously with frequency due to the propagation characteristics of the microwave network.
* The transitions between **+180° and −180°** are caused by phase wrapping in ADS and do not represent physical discontinuities.

## Results

The simulated six-port network successfully demonstrates:

* Equal power division
* Approximately **−6 dB** output magnitude
* Expected phase characteristics
* Balanced output responses over the selected frequency range

## Conclusion

The simulation results closely match the expected theoretical behaviour of the six-port microwave network. The approximately **−6 dB** output magnitude confirms the expected power division, while the phase responses demonstrate the signal relationships introduced by the hybrid couplers.

## Software Used

* Keysight Advanced Design System (ADS)

