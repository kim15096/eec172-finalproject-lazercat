# LazerCat

By: Andrew Kim & Rocco Scinto

## Description

LazerCat is an innovative toy designed for cat owners, enabling them to interact with their pets remotely through a controlled laser pointer and live video feed. Utilizing AWS WebRTC and IoT for seamless cloud integration, the system consists of three main components: a home-based CC3200 module, an away CC3200 module, and a Raspberry Pi. The home module manages local motion detection and AWS-triggered laser control, while the away module allows users to send commands via an IR remote, displaying these commands on an OLED screen and forwarding them to AWS. The Raspberry Pi handles video streaming, activating upon motion detection or user request to provide live footage of the cat activities. Implementation goals range from basic laser activation and motion sensor functionality to advanced features like pre-programmed laser routines, sound playback, and real-time video streaming. The project aims to keep cats entertained and active, providing peace of mind to owners.
