# CanSat-Satellite-Prototype.
CanSat Satellite Prototype – SUPARCO Space Camp 2026: 
This project involves the design and development of a CanSat (can-sized satellite) based on the ESP32 architecture, integrating multiple subsystems for real-time environmental monitoring and data acquisition. 
The system collects sensor data from onboard modules including a camera for imaging, an accelerometer and gyroscope for motion sensing, a pressure sensor for atmospheric readings, and a GPS module for location tracking and altitude estimation. 
Data is acquired at optimized sampling rates, accurately timestamped, and packetized before being wirelessly transmitted from the CanSat to the ground station. 
The ground station, also powered by ESP32, receives the data packets and forwards them to a PC via a serial (COM) port. 
A custom-built Python-based GUI application processes, visualizes, and logs the incoming telemetry data in real time, enabling effective monitoring and analysis.
The hardware was calibrated under varying conditions such as changes in altitude and velocity to ensure measurement accuracy and system reliability. 
The CanSat was successfully launched, demonstrating stable communication, efficient data transmission, and precise tracking of landing coordinates, reflecting a complete end-to-end implementation of an embedded telemetry system.
