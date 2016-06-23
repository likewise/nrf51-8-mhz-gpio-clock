nrf51-short-pulse
=================

A simple project showing how to use the a TIMER and GPIOTE, connected with the PPI to generate a short pulse.
The pulse width can be as short as 62.5 ns or any positive multiple thereof. Verified on oscilloscope.

Derived from NordicSemiconductor/nrf51-8-mhz-gpio-clock example. (Forked on GitHub.)

Requirements
------------
- nRF51 SDK version 5.1.0
- nRF51822 Development Kit 

The project may need modifications to work with later versions or other boards. For instance, if you have an Evaluation Kit, you can make it work by changing the BOARD define in the project settings. 

To compile it, clone the repository in the nrf51822/Board/pca10001/s110/ folder.

About this project
------------------
This application is heavily based on one of the applications that has been built by the support team at Nordic Semiconductor, as a demo of some particular feature or use case. It has not necessarily been thoroughly tested, so there might be unknown issues. It is hence provided as-is, without any warranty. 
