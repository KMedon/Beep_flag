# Football Referee Flags with LoRa Communication
# Overview
This repository houses my engineering project, a cutting-edge set of football referee flags designed with LoRa technology for seamless and effective wireless communication. Aimed at transforming the communication dynamics for referees, especially in lower leagues where advanced communication tools may not be readily available, this project seeks to enhance decision-making accuracy and efficiency on the field.

# Genesis
The inspiration behind this project was to bridge the communication gap faced by referees in lower-tier football leagues. These leagues often lack the resources for sophisticated communication devices, impacting the referees' ability to make quick and accurate decisions. By developing a reliable and easy-to-use set of referee flags with a receiver, this project aims to provide a cost-effective solution that elevates the quality of game officiating across all levels of play.

# Technology
Utilizing LoRa (Long Range) technology at the 868 MHz frequency enables dependable wireless communication over considerable distances. The core of this system is the RAK3172 module, powered by an STM32WLE5 microcontroller, chosen for its performance and reliability. The project was developed in STM32CubeIDE, incorporating the Sub-GHz PHY library for managing wireless communications efficiently.

# Mechanical Design and Testing
The project extends beyond software and communication technologies to include detailed mechanical design and rigorous testing. Files outlining the mechanical construction and assembly of both the flags and the receiver are provided, alongside results from tests designed to evaluate current consumption and the communication range, ensuring system efficiency and field readiness.

# PCB Design
A pivotal aspect of the project is the meticulously designed PCBs for the flag and receiver units. These designs prioritize low power consumption and effective LoRa communication, with durability and component reliability being key considerations to withstand the physical demands of football matches.

# Software
A standout feature of the software is the intuitive interaction between the referee flags and the receiver. When a referee presses the button on a flag, it triggers a buzzer on the receiver unit. This immediate audio feedback ensures that messages are conveyed promptly and unmistakably, supporting referees in maintaining focus on the game without distractions.

The software is crafted with attention to efficiency and responsiveness, ensuring seamless communication between devices. Detailed documentation and source code are available in the src folder, inviting exploration and modification.

# Features
Long-range LoRa communication (868 MHz) tailored for referees in lower leagues
Custom PCB designs for flag and receiver, emphasizing efficiency and durability
In-depth mechanical designs with extensive durability and performance testing
Immediate audio feedback via receiver buzzer upon flag button press
Developed in STM32CubeIDE using the Sub-GHz PHY library
