This repository contains documents of 'secure MAVLink' project.

# Secure mavlink
PX4 Autopilot is opensource drone software, and QGC(qgroundcontrol) is command center of ground. These component communicate with each other using MAVLink protocol (Micro Air Vehicle Link).  
Below list is implementations to enhance security of MAVLink protocol.  
* Add payload encryption support of MAVLink protocol itself.  
Github repository is [here(pymavlink)](https://github.com/Lumy0726/pymavlink/).  
* Implement encrypted MAVLink communication for PX4 and QGC.  
Github repository is [here(PX4)](https://github.com/Lumy0726/PX4-Autopilot/).  
Github repository is [here(QGC)](https://github.com/Lumy0726/qgroundcontrol/).  

# Documents
* Middle report paper, 3 page, pdf.  
[중간보고서](./report_middle.pdf)  

# Link of other edited repository
* MAVLink repository, which includes 'pymavlink' repository as submodule.  
[here(mavlink)](https://github.com/Lumy0726/mavlink/).  
* 'c_library_v2' repository, which is pre-builded header file of MAVLink (protocol version 2.0 with C language).  
[here(c_library_v2)](https://github.com/Lumy0726/c_library_v2/).  
