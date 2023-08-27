# modbus OPCUA class 
To familiarize with Modbus(RTU/TCP) and OPC UA protocols with exercises. 
### NOTE: Modbus - https://modbus.org/; OPC UA - https://opcfoundation.org/
## Exercises
1. Install software: a. For Modbus: ModbusPoll and ModbusSlave. (from https://www.modbustools.com/) b. For OPC UA: Edgelink (from Adventech.com)
2. Modbus test: PC (ModbusPoll) to PC (ModbusSlave)
3. Modbus/RTU test: PC (ModbusPoll) to the devices (humi/temp sensor, relay i/o, power meter)
4. Modbus/TCP test with WIFI Gateway WISE 4051: PC (ModbusPoll) to the devices (humi/temp sensor, relay i/o, power meter); Notice: PC Modbus tool (ModbusPoll) should acquire data by the mapping register of WISE4051 (like 1001, 1002, 1003...), but the devices' original register.    
6. OPC UA Data Center: create tags (ID1: humi/temp., ID2: I/O relay, ID3: Power meter) with EdgeLink
7. OPC UA Service: configure tags for the OPC server
8. Install the OPC UA client and approach the OPC UA server: UaExpert Client, and use it to access OPC UA data (built at OPC UA Service)
9. I/O Box connection exercise: wire sensor, switch, and alarm to ADAM6717 (OPC UA gateway) and WISE4051 (WiFi gateway); conduct wet contact and alarm test on ADAM 6717 and dry contact on WISE 4051.
## Demo video: Introduction to modbus and OPC UA connection 
1. Modubus connection demo: https://youtu.be/_p7lfhecDnc
2. OPCUA connection demo: https://youtu.be/EOVrADHYUzw
3. Modify modbus slave ID: https://youtu.be/nAL0iaEnk3s
4. I/O box test: wet contact, output (ADMA6717), dry contact (WISE 4051);https://youtu.be/bSM6B_Wz3Iw
## Device manual 
1. ASUS WIFI AP manual (N router)
2. ADAM 6700 gateway manual (including ADAM 6717, OPC)
3. WISE 4000 gateway manual (including WISE 4051, RS485)
4. SDM 640 power meter manual
5. Relay I/O (RS485, modbus RTU)
6. SHT20 Humi/Temp sensor
7. Option 1: Humi/Temp sensor
8. Option 2: power meter
## Software
1. Adam utility
2. Adam 6717
3. IP scanner
4. Modbus (Modbus Poll and Modbus Slave)
5. Serialport Utility(modify modbus slave ID)
6. UAexpert (free OPC UA client)
7. WISE4051 (use browser to login)
8. EdgeLink_config (ADAM 6717 configration sample)
