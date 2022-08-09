# TwinCAT-Projects

### In this repository you'll find TwinCAT related project

Feel free to use the provided functions as you which, however be aware that there is no guarantee that
the software in this repository may not work well for your application

This is not an official Beckhof repository and it's not related to it at all.

**ErrorTracking** => this software allows you to track errors on you software:
Suppose your application has a division by zero, an EtherCAT problem and so on...
This software helps you to track those errors and log it into persistent memory

**AlarmHistory** => this project is a sample application of how you can make a simple
Alarm history that works with the regular PLC-HMI/PLC-HMI Web.
It helps you to have your own alarmhist functionlity since the regular package does
not provide it.

**SampleTime** => Various functions to help you do
* Time scheduling - Activate a given output at a certain day/time of the week
* read time from the IPC on PT-BR format
* change both time and date of the IPC
* count time for machines (Hour meter) that counts time based on a persistent/retain variable
* Provide a function block that will calculate quality functions for time such as average, standard deviation and so on
