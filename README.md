
## Description
This project is for feasibility/performance testing and cost analysis of embedded image preprocessing, server based processing, and hybrid implementations. The system preprocesses video data and is configurable to detect movement. We then send data to a local server. It is designed to run on various camera operating systems and perform real-time processing.

## This project will consist of: 
1. different implementations for different hardware constraints
2. Various protocol decsions
3. Network Configurations with Client and Server
4. Various levels of preprocessing, local to camera only, server processing only and hybrid implementations.

## Multithreaded Server Independent of Client ****

### Protocols to be tested
1. RTP / SRTP
2. RTSP over SSP
3. RTP/RTCP

### Preprocessing To Test 
1. Noise Reduction
2. Compression
3. Segmentation
4. Event based analysis
5. More to come...

### Network Processing to test
1. No image analysis on camera hardware. Do all computations on server
2. All Preprocessing. No server based anaylsis
3. Mixture of preprocessing on camera hardware + computation on server

## Features
- **Real-Time Motion Detection**: Detects motion in the camera's field of view and triggers alerts / performs additional processing or flag to server for additional analysis.
- **Network Communication**: Sends motion detection alerts and data to server.
- **Security**: Secure data transmission protocols while retaining minimal latency.
- **Low Resource Consumption**: Optimized to run with minimal resource usage. Test requirements for hardware, perform regression test for cost/performance.
