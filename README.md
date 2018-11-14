# AB_CTRL_LGX_AOIs
Allen Bradley Control Logix PLC AOIs
All the AOIs are designed as objects such that the objects in an HMI/SCADA system can be created to connect directly to the PLC AOIs by typing in the tag designation for the equipment.  Example: Pump 101 tag is 'P101'.  Created a 'P101' child object in the PLC by using the programmer generated AOI parent object.  If the object code (with correct attributes) is created in the HMI/SCADA software, a programmer simply creates a child object (pointed at the correct PLC) from the HMI/SCADA parent object with the same tag designation of 'P101".  The objects in the PLC and HMI are then connected.  The manual part of this process is to map the PLC Input/Output (I/O) tags to the PLC AOI Attributes.  I have experienced having manual control of a motor within 30 minutes of starting the program (I/O must be completely verified as operational).
  
SIM_AOI_VSM.L5K >> Variable Speed Motor module simulator. Code designed to simulate a VFD driven motor.
SIM_AOI_FVNR.L5K >> Full Voltage Non-Reversing motor module simulator. Code designed to simulate a standard motor starter.
ES_AOI_WALL_CLOCK.L5K >> Generates time values from the PLC wall clock (typically used for time stamping and sync Functions).
ES_AOI_RTM_LDR.L5X >> Runtime Meter
ES_AOI_FLW_TOT.L5X >> Flow Totalizer
EM_AOI_VSM.L5X >> Variable Speed Motor Module
EM_AOI_TSV.L5X >> Two State Valve Module
EM_AOI_MVM.L5X >> Modulating Valve Module
EM_AOI_FVM.L5X >> Full Voltage Motor Module
EM_AOI_DIM.L5X >> Digital Input Module
EM_AOI_AIM.L5X >> Analog Input Module
AOI_LD_LG.L5X >> Lead-Lag Module
AOI_LD_ALT.L5X >> Motor Alternator Module
