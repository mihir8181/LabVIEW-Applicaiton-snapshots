## LabVIEW-Application-snapshots 
***Snapshots of LabVIEW applications front end, GUI of Utilities and ATEs.***


**1) Programmable Multioutput DC Power Supply GUI**

Designed GUI and Developed Application for Monitoring, and Controlling of DC power supply through USB physical layer. 
Modbus protocol used for communication of data between hardware and LabVIEW App. 
Implemented a file system in the application. 
NI-VISA tool, NI Modbus library, Microsoft SQL tools, File Manager system used.
![Programmable Multioutput DC Power Supply GUI](https://github.com/mihir8181/LabVIEW-Applicaiton-snapshots/blob/master/DC%20Power%20Supply%20monitoring%20%26%20controlling%20application.png)


**2) ITC E-Cigarette MemCOM (Memory Communication) Application**

This application is to communicate with the memory of ITC E-cigarette.
To store/read values of Max-min puff count, Max-min Puff time, serial number, etc. in/from the memory of E-cigarette.
The application is based on Serial communication over USB protocol.
![ITC E-Cigarette MemCOM (Memory Communication) Application](https://github.com/mihir8181/LabVIEW-Applicaiton-snapshots/blob/master/ITC%20ECG%20MEMcom.png)

**3) Industrial UPS MONITORING Application**

Designed GUI and Developed application for Monitoring Industrial UPS Parameters through UART.
The application consists of Graphical Representation of all UPS and power parameters.
Features of application are as follows
*User notification over Email for Critical parameters,

*Alarm for critical parameters,

*Event logging,

*report genration.

Communication is based on RS 232.
![Industrial UPS MONITORING Application](https://github.com/mihir8181/LabVIEW-Applicaiton-snapshots/blob/master/Industrial%20UPS%20monitoring%20utility.png)

**4) Magnetic Rotary Encoder GUI**

The magnetic Rotary Encoder is communicated with CPU and other devices over CAN protocol. 
This applicaiton Controlling and monitoring the all CAN devices.
Designed GUI and Developed Application for Communicating, Monitoring and Controlling CAN devices using CAN analyzers like:
1) IXXAT 

2) CANalyst-2. 

The application is Based on shared DLL. 
Data can be sent from the application or get/receive from CAN device via analyzer. 
CAN analyzer communicate to the application through DLL. 
It is a Master /slave communication between CAN devices(Slave) and LabVIEW application(Master).
Security level is added in the application with RC4 Encryption ( Crypto- Tools ).
![Magnetic Rotary Encoder GUI](https://github.com/mihir8181/LabVIEW-Applicaiton-snapshots/blob/master/Magnetic%20rotary%20encoder.png)



**5) Marway ATE Applications GUI**

Designed GUI and Developed an application in LabView for calibration and 
continuous monitoring of 3Phase parameters over I2C protocol.
* Here I have used xdimax's SUB-20 Multi Interface USB Adapter, Which is a I2C to USB converter. 
* Application has met customers following requirements like,
a) Phase selection and configuration of their card through application,
b) Phase calibration,
c) Phase Parameter monitoring
d) Fetch card status, etc.
![Marway ATE Applications GUI](https://github.com/mihir8181/LabVIEW-Applicaiton-snapshots/blob/master/Marway%20Power%20Solution%20ATE.png)
