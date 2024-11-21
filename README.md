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

**BasicUtils** => Functionalities to help with several situations

**TempControlSample** => Sample use of the Temperature controller library
* In this sample here we have a visualization which help us understand how to use the temperature controller library
* It has been made so that one might be able to use it well for a heating application
* Althought that are some of the parameters used in the cooling process it has not been tested for such use and must be adapted

**SimulComponents** => Library that allows the user to simulate various components, such as cilinders, silos and so on

**Safety** => Set of libraries that help you diagnose safety FBs, groups and connections
* Just map state, diag, input and output to the PLC and use these function blocks to 
* Help diagnose your safety application.
* **Attention** This project is not intended to be used in any particular safety related application
it's basically just a sample
* At the moment only E-Stop function block diagnose is implemented, however other function
blocks can be easily inserted.

**CsvTextManip** => Sample on how to write and read csv files in text mode
* Functionality to both read and write files to the disk in order to store information on .csv files format
* Ideal for saving big tables and loading them afterwards
* One might need to adapt in order to fit this project to some particular necessity.