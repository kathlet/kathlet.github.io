---
title: "Live Python Data Plotter for Flight Testing"
excerpt: "Engineered a custom Python GUI to provide real-time visualization of streaming flight data, enabling live system monitoring and post-flight analysis of large datasets.<br/><img src='/images/live_plotter.png'>"
collection: portfolio
---

### Project Overview
During live flight tests, immediate feedback on an aircraft's state is crucial for safety and efficiency. To solve this, I developed a custom Python GUI that plots essential telemetry in real-time.

The application listens to a serial port connected to a ground-based receiver, which receives a live data stream from the aircraft's onboard transmitter.

### Key Features & Application
* **Real-Time Visualization:** The GUI parses incoming data and dynamically updates plots, providing immediate insight into critical flight parameters.
* **System Monitoring:** This tool allows for live monitoring of system health and performance during flight tests, enabling a quick diagnosis of any potential issues.

The image below shows the plotter visualizing a set of randomized sinusoids, simulating the type of data received from a port during a test.

![Live Plotter for Randomized Sinosoidals from Data Received from a Port](/images/live_plotter.png){:loading="lazy"}