
## Description
This project develops an embedded C program for a physical camera system capable of detecting motion. The system preprocesses video data, detects movement, and sends the information to a local server. It is designed to run on the camera's operating system, utilizing the cameras hardware to perform real-time processing.

## This project will consist of: 
1. different implementations on different hardware
2. Various protocol decsions
3. Network Configurations with Client and Server
4. Various levels of preprocessing

## Multithreaded Server Independent of Client ****

### Protocols to be tested
1. RTP / SRTP
2. RTSP over SSP
3. RTP/RTCP

### Preprocessing To Test
1. Noise Reduction
2. Compression
3. Segmentation

## Features
- **Real-Time Motion Detection**: Detects motion in the camera's field of view and triggers alerts.
- **Network Communication**: Sends motion detection alerts and data to a configured server.
- **Security**: Implements secure data transmission protocols to ensure data integrity and confidentiality.
- **Low Resource Consumption**: Optimized to run with minimal resource usage, suitable for embedded systems.


# Copyright Notice
Copyright (c) 2024 Michael Lammens

All rights reserved.
The code and other materials in this repository are made available for viewing only. No permissions are granted for direct distribution or creation of derivative works.
