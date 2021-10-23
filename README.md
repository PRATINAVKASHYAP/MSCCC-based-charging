# MSCCC-based-charging
The model designed is a 48V (Buss Voltage) to 25V (Battery Voltage) bidirectional boost converter with a 5 Stage Constant Current Control.

The converter is controlled using two PI control loops. One operates during the charging stage and the other operated during discharging stage. During the Charging State a 5 Stage Constant Current Control is used as the charging time and the charging of Multi (5) Stage Constant Current Control (MSCCC) was found better than Constant Current Constant Voltage method (ref paper: https://doi.org/10.1109/ITEC-AP.2016.7512982)

The DC load voltage is set to be at a constant 48V at both charging and discharging stages. The battery pack used is a 7s19p (I took the data of charging rates and discharge rates from the LG INR18650 B4 2600mAh cell data sheet).

The Results are as follows:


