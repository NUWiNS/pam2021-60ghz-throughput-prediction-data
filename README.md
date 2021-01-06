# Throughput Prediction on 60 GHz Mobile Devices for High-Bandwidth, Latency-Sensitive Applications
Data from our PAM 2021 publication used for throughput prediction in static and mobile scenarios

Each folder contains file(s) totalling 10 hours of throughput data under 3 scenarios:

1. Static (Section 3.2)
2. Mobile (Section 3.3)
3. Applications (Section 3.4)<br>
  a. VR<br>
  b. ABR

Please refer to the corresponding sections in the paper for more details regarding the scenarios.

Each file contains the following data for every 10 ms (each row):

* Android sensor data
  * Positional data (Azimuth, Pitch, Roll)
  * Accelerometer data (along x-, y- and z-axes)
* 60 GHz link data (reported by the wil6210 driver)
  * MCS
  * Tx Sector
  * Link Status
  * Signal Quality Indicator (SQI)
  * RSSI
