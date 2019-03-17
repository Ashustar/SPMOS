SPMOS

In Our Project XILINX PYNQ Z2 is used as a Main Processing Unit ,also used as a database which Stores Data and applies Machine Learning Algorithm for Early Prediction of Errors in the Power Grid Prior to the fault. It maintains Grid Database and Sends Reports to the Authority periodically. This Report is composed of Grid Condition,Transformer Health,life Expectency,Voltage and Current readings,faulty Pole Tracking data,short circuit detection,Power Theft info,Transformer switching.

We are Configuring Arduino I/O ports for Controlling Power unit and to Setup all default Data

KNN Algorithm is used for Electric grid health prediction and to add data into csv file .

Invoking the grid health prediction algorithm in the code which takes data from the code and predicts the Health and Power theft based on sensor data.

A Report mail will be sent to Power management Regarding the Grid Network reports periodically with format

Data input From Sensors

Seasons 
Voltage 
Current 
Transformer Core Temperature 
Grid Load 
Blown Fuses : 


Gives Health of Transformer

season= 1
The predicted class for sample [Season ,core Temp ,power Load ,blown Fuses] : Health of Transformer
The predicted class for sample [1, 80, 52, 0] is : normal
Number of votes : 4 out of 5
