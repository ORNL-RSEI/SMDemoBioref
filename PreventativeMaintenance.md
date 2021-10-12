# Preventative Maintenance - Biomass Pretreatment

## University of Florida's Stan Mayfield Demonstration Biorefinery

The Biorefinery's process engineers were tasked with preventing disruptions in operation and preserving worker safety through diligent surveying and maintenance of the various equipment within the thermochemical pretreatment system. The biomass preatreatment system was a highly complex series of equipment that operated under high pressure with corrosive chemicals, thereby making it prone to malfunction. A series of data tracking tools were developed to be routinely utilized by the process engineers. The data provided herein are not entirely complete, and empty cells are denoted by NA.

### Table of Contents

[Start Up Summary](#start-up-summary)  
[Steady State Shift Summary](#steady-state-shift-summary)  
[Steady State Gear Drive Temperature](#steady-state-gear-drive-temperature)  
[General Maintenance](#general-maintenance)  
[Boiler Maintenance](#boiler-maintenance)  
[Pretreament Blowtank Ball Valves](#pretreament-blowtank-ball-valves)  
[Pretreament Blowtank Knife Gates](#pretreament-blowtank-knife-gates)  
[Gear Drive Oil](#gear-drive-oil)  
[Grease Addition](#grease-addition)

#### Start Up Summary  

Process engineers would record qualitative and quantitative data during the start-up sequence of the pretreatment system while the Biorefinery was in campaign opearation. All temperatures are provided in degrees Fahrenheit, and all pressures are provided in pound per square inch.  
Data: [PM01.csv](PM/PM01.csv)  

*Summary Table*
| Number | Name | Value Example |
| ----------- | ----------- | ----------- |
| 1 | Date | 2015-01-20 *to* 2015-08-08 |
| 2 | Engineer | JS, *etc.* |
| 3 | Feed_System_Air_Purge_Lines | Good; See notes |
| 4 | Tension_Sensor_Cablevey_1 | Good |
| 5 | Tension_Sensor_Cablevey_2 | Good |
| 6 | Metal_Detector | Good; See notes |
| 7 | Boiler | Good; See notes |
| 8 | Water_Hardness | Good |
| 9 | Emergency_Vent | Clear; Good |
| 10 | Blow_Back_Dampner_Position | Fully closed; Good; Not closed fully; See notes |
| 11 | Blow_Back_Dampner_Pressure | 39, *etc.* |
| 12 | Seal_Water_Filter_Inlet_Pressure | 60, *etc.* |
| 13 | Seal_Water_Filter_Outlet_Pressure | 54, *etc.* |
| 14 | High_Pressure_Seals | Good; See notes |
| 15 | Low_Pressure_Seals | Good |
| 16 | Top_Knife_Gate_Flush_System | Good |
| 17 | Top_Knife_Gate_Movement | Good |
| 18 | Top_Knife_Gate_Packing | Good; See notes |
| 19 | Bottom_Knife_Gate_Flush_System | Good |
| 20 | Bottom_Knife_Gate_Movement | Good; See notes |
| 21 | Bottom_Knife_Gate_Packing | Good; See notes |
| 22 | Top_Ball_Valve | Good; See notes |
| 23 | Bottom_Ball_Balve | Good |
| 24 | Vibrator_Pressure | 40, *etc.*; Off |
| 25 | Plug_Screw_Rinsate | Good |
| 26 | Pre-Steam_Bin_Temp | 43, *etc.*|
| 27 | Blow_Chamber_Steam_Exhaust_Cooling_Coil | On; See notes |
| 28 | Hydrolyzer_Vent_Position | Cracked; See notes |
| 29 | System_Pressure_Rise | Good; Very smooth; See notes |
| 30 | Pre-Steam_Livebottoms_Start_Pressure | 100, *etc.* |
| 31 | Time_to_Pressure_After_Steam | 30, *etc.*; See notes |
| 32 | System_Pressure | 150, *etc.* |
| 33 | System_Temp | 185, *etc.* |
| 34 | Notes | *Desc.* |

#### End of Shift Summary

Process engineers would record qualitative and quantitative data at the end of their shifts while the Biorefinery was in campaign opearation. The data were used by the next shift to understand the status of operation. In addition, the data were helpful in writing Campaign Summaries once the Campaign was complete. All temperatures are provided in degrees Fahrenheit, and all pressures are provided in pound per square inch.  
Data: [PM02.csv](PM/PM02.csv)  

*Summary Table*
| Number | Name | Value Example |
| ----------- | ----------- | ----------- |
| 1 | Date | 2015-01-20 *to* 2015-08-08 |
| 2 | Time | 02:00 *to* 24:00 |
| 3 | Engineer | JS, *etc.* |
| 4 | Feed_System | Ran well; Good; Shut down; See notes |
| 5 | Feedbin_Level | Good; Full; See notes; *Desc.* |
| 6 | Signs_Pre-Steam_Bin_Chute_Clogging | Good; See notes; *Desc.* |
| 7 | Boiler | Good; Shut down; *Desc.* |
| 8 | High_Pressure_Seals | Good; Shut down; See notes |
| 9 | Low_Pressure_Seals | Good; Shut down; See notes |
| 10 | Seal_Water_Filter_Inlet_Pressure | 59, *etc.* |
| 11 | Seal_Water_Filter_Outlet_Pressure | 53, *etc.*; See notes |
| 12 | Top_Knife_Gate_Flush_System | Good; See notes |
| 13 | Top_Knife_Gate_Movement | Good; See notes |
| 14 | Top_Knife_Gate_Packing | Good |
| 15 | Bottom_Knife_Gate_Flush_System | Good |
| 16 | Bottom_Knife_Gate_Movement | Good; See notes |
| 17 | Bottom_Knife_Gate_Packing | Good |
| 18 | Top_Ball_Valve | Good; See notes; *Desc.* |
| 19 | Bottom_Ball_Valve |Good; See notes; *Desc.*  |
| 20 | Gear_Drive_Temp {1} | Good; See notes; *Desc.* |
| 21 | Vibrator_Pressure | 20, *etc.*; See notes; *Desc.* |
| 22 | Hydrolyzer_Vent_Positon | Closed; Cracked; Open; *Desc.* |
| 23 | Squeezing_Hz | Yes; No; See notes; *Desc.* |
| 24 | Blow_Tank_Samples | 1, *etc.*; Yes; No |
| 25 | Percentage_Presteam_Livebottom_Speed | 80, *etc.*; *Desc.* |
| 26 | Flow_Rate_Test | !!!!!!!!!! |
| 27 | Shift_Change_System_Pressure | 149, *etc.*; Shut down; See notes |
| 28 | Shift_Change_System_Temp | 363.2, *etc.* |
| 29 | System_Shut_Down_During_Shift | Yes; No |
| 30 | If_Shut_Down_Boiler_Blow_Down | Yes; No; See notes |
| 31 | BBD_Fully_Close | Yes; Not completely |
| 32 | Wash_Down | Yes |
| 33 | Notes | *Desc.* |

1 Should all be below 150.  

#### Steady State Gear Drive Temperature

Process engineers would use IR thermometer guns to record temperatures of the auger gear drive casings in the preteatment system to ensure drives were not overheating. Only one record is provided, and all temperatures are provided in degrees Fahrenheit.  
Data: [PM03.csv](PM/PM03.csv)  

*Summary Table*
| Number | Name | Value Example |
| ----------- | ----------- | ----------- |
| 1 | Date | 2015-02-27 |
| 2 | Time | 02:30 |
| 3 | Engineer | KW |
| 4 | Feed_Bin_Reducer | NA |
| 5 | Feed_Bin_4-Shaft_Transmission | 53 |
| 6 | Feed_Bin_Collecting_Conveyor | 105 |
| 7 | Pre-Steam_5-Shaft_Transmission | NA |
| 8 | Plug_Screw_Feeder | 125 |
| 9 | High_Shear_Mixing_Conveyor | 127 |
| 10 | Hydrolyzer_Reducer | NA |
| 11 | Hydrolyzer_Discharge_Screw | 132 |
| 12 | Blow_Tank_Agitator | 92 |
| 13 | Screw_Press_Feed_Screw | 112 |
| 14 | Screw_Press_Reducer | 112 |
| 15 | Reversing_Conveyor | 126 |

#### General Maintenance

Process engineers would perform and log general maintenance activities on the pretreatment system as needed. This preventative maintenance was performed when the Biorefinery was not in campaign operation.  
Data: [PM04.csv](PM/PM04.csv)  

*Summary Table*
| Column | Name | Value Example |
| ----------- | ----------- | ----------- |
| 1 | Date | 2014-04-03 *to* 2015-07-01 |
| 2 | Engineer | JS, *etc.* |
| 3 | Bolt_Tightness {1} | *Desc.* |
| 4 | Clean_Seal_Filter_Screens {2} | Done |
| 5 | Dismantle_&_Clean_Screw_Press {3} | Done; *Desc.* |
| 6 | Clean_Reversing_Conveyor_in_Forward_Direction {4} | Yes; No; *Desc.* |
| 7 | Hydrolyzer_Non-Driven_End_Tolerance {1,5} | *Desc.* |
| 8 | Belts_Checked {1} | Done; *Desc.* |
| 9 | Plug_Screw_Inspection {3} | *Desc.* |
| 10 | Notes | *Desc.* |

1 Every 750 hours of operation.  
2 When differential was greater than 5 psi.  
3 As needed.  
4 Prior to every liquefaction CIP.  
5 Tolerance should not exceed 0.06" radially. Torque on bolts should be 100 lb-ft.  

#### Boiler Maintenance

Process engineers would routinely perform and log maintenace activities on the Biorefinery's boilers (Fulton & Lattner). This preventative maintenance was performed when the Biorefinery was not in campaign operation.  
Data: [PM05.csv](PM/PM05.csv)  

*Summary Table*
| Number | Name | Value Example |
| ----------- | ----------- | ----------- |
| 1 | Date | 2015-01-15 *to* 2015-07-07 |
| 2 | Engineer | JS, *etc.* |
| 3 | Fulton | Yes |
| 4 | Lattner | Yes |
| 5 | Blowdown | Yes; No |
| 6 | Feedwater_Tank_Flush {1} | Yes; No |
| 7 | Boiler_Additive_Level {2,3} | Low; Good; *Desc.* |
| 8 | Pressure_Relief_Valve_Test {3} | Good |
| 9 | High_Pressure_Limit_Test {3} | Good |
| 10 | Low_Level_Alarm_Test {3} | No; Good |
| 11 | Level_Sensor_Cleanse {3} | Yes; No |
| 12 | Salt_Level {2} | Good; Ok; See notes |
| 13 | Electrical_Connection_Tightness {1} | Yes; No; Good |
| 14 | Pipe_Connection_Tightness {1} | Yes; No; Good |
| 15 | Pump_Hydraulic_Oil {1} | No; Exchanged; *Desc.* |
| 16 | Boiler_Inspection_Done {4} | Done; *Desc.* |
| 17 | Notes | *Desc.* |

1 Every four months.  
2 Every use.  
3 Indicate if a new container was installed.  
3 Twice per year.  
4 Once per year by contractor.  

#### Blowtank Ball Valves

Process engineers would perform and log maintenance activities on the two automated, 8 inch ball vales that were used to discharge pretreated biomass from the pressurized hydrolyzer to the blow tank. This preventative maintenance was performed when the Biorefinery was not in campaign operation.  
Data: [PM06.csv](PM/PM06.csv)  

*Summary Table*
| Number | Name | Value Example |
| ----------- | ----------- | ----------- |
| 1 | Date | 2015-02-04 *to* 2015-03-30 |
| 2 | Engineer | JS, *etc.* |
| 3 | Top_Valve {1} | See notes; *Desc.* |
| 4 | Bottom_Valve {1} | *Desc.* |
| 5 | Notes | *Desc.* |

1 As needed.  

#### Blowtank Knife Gates

Process engineers would perform and log maintenance activities on the two automated, 8 inch knife gate vales (alternates to the ball valves) that were used to discharge pretreated biomass from the pressurized hydrolyzer to the blow tank. This preventative maintenance was performed when the Biorefinery was not in campaign operation. The data columns specify which of the knife gates are applicable. The top knife gate is abbreviated TKG and the bottom knife gate is abbreviated BKG.  
Data: [PM07.csv](PM/PM07.csv)  

*Summary Table*
| Number | Name | Value Example |
| ----------- | ----------- | ----------- |
| 1 | Date | 2015-01-09; 2015-03-25 |
| 2 | Engineer | JS; PW |
| 3 | TKG_Above_Pipe_Biomass_Accumulation | *Desc.* |
| 4 | TKG_Scraper | *Desc.* |
| 5 | TKG_Gate | *Desc.* |
| 6 | TKG_Packing | *Desc.* |
| 7 | TKG_Seat_Seal {1} | *Desc.* |
| 8 | TKG_O-Rings | *Desc.* |
| 9 | TKG_Flush_Port | *Desc.* |
| 10 | BKG_Scraper | *Desc.* |
| 11 | BKG_Gate | *Desc.* |
| 12 | BKG_Packing | *Desc.* |
| 13 | BKG_Seat_Seal {1} | *Desc.* |
| 14 | BKG_O-Rings | *Desc.* |
| 15 | BKG_Flush_Port | *Desc.* |

1 Indicate if a new seal was installed.

#### Gear Drive Oil

Process engineers would test and/or exchange oil in the auger gear drives as needed. This preventative maintenance was performed when the Biorefinery was not in campaign operation. It was recommended that oil be checked every 500 hours of operation, and oil replaced every 2,500 hours with mineral lubricant and every 10,000 hours with 460 synthetic. Gear drive oil exchange information is provided here and in the file [PM08.5.csv](PM/PM08.5.csv).  
Data: [PM08.csv](PM/PM08.csv)  

*Summary Table*
| Number | Name | Value Example |
| ----------- | ----------- | ----------- |
| 1 | Date | 2015-01-05; 2015-02-27 |
| 2 | Engineer | JS |
| 3 | Feed_Bin_Reducer | Oil exchanged |
| 4 | Feed_Bin_4-Shaft_Transmission | Oil exchanged |
| 5 | Feed_Bin_Collecting_Conveyor | Oil exchanged |
| 6 | Pre-Steam_5-shaft_Transmission | *Desc.* |
| 7 | Plug_Screw_Feeder | Oil exchanged |
| 8 | High_Shear_Mixing_Conveyor | Oil exchanged |
| 9 | Hydrolyzer_Reducer | See notes |
| 10 | Hydrolyzer_Discharge_Screw | Oil exchanged |
| 11 | Blow_Tank_Agitator | Oil exchanged |
| 12 | Screw_Press_Feed_Screw | See notes |
| 13 | Screw_Press_Reducer | Oil exchanged |
| 14 | Reversing_Conveyor | Oil exchanged |
| 15 | Notes | *Desc.* |

*Exchange Information*
| Reducer/Transmission/Drive | Drive_Type | Oil_Type | Gallons_Needed | Number_500mL_Bottles | Details |
| ----------- | ----------- | ----------- |----------- | ----------- | ----------- |
| Feed Bin Reducer | Sumitomo | 150 Mineral | 4.8 | 36.336 | The oil level should reach the bottom of the shaft |
| Feed Bin 4-Shaft Transmission | Metso Custom | 460 Synthetic | 4.8 | 36.336 | NA |
| Feed Bin Collecting Conveyor Drive | Falk | 460 Synthetic | 1.1 | 8.327 | NA |
| Pre-Steam 5-shaft Transmission | Metso Custom | 460 Synthetic | 0.7 | 5.299 | NA |
| Plug Screw Feeder Drive | Falk | 460 Synthetic | 3.2 | 24.224 | NA |
| High Shear Mixing Conveyor Drive | Falk | 460 Synthetic | 0.4 | 3.028 | NA |
| Hydrolyzer Reducer | Sumitomo | 150 Mineral | 0.92 | 6.9644 | The oil level should reach the bottom of the shaft |
| Hydrolyzer Discharge Screw Drive | Falk | 460 Synthetic | 0.3698 | 2.8 | NA |
| Blow Tank Agitator Drive | Falk | 460 Synthetic | 1.6 | 12.112 | NA |
| Screw Press Feed Screw Drive | Falk | 460 Synthetic | 0.19 | 1.4383 | NA |
| Screw Press Reducer | Sumitomo SM-CYCLO | 150 Mineral | 0.66 | 4.9962 | The oil level should reach the bottom of the shaft |
| Reversing Conveyor  | Falk | 460 Synthetic | 1.1 | 8.327 | NA |

#### Grease Addition

Process engineers would apply Thermaplex multipurpose grease (Lithium Complex) to auger bearings as needed.  
Data: [PM09.csv](PM/PM09.csv)  

*Summary Table*
| Number | Name | Value Example |
| ----------- | ----------- | ----------- |
| 1 | Date | 2015-01-12 *to* 2015-07-06 |
| 2 | Engineer | JS, *etc.* |
| 3 | Feed_Bin_Livebottoms {1} | 2 pumps, *etc.*; See notes |
| 4 | Feed_Bin_Collecting_Conveyor {2} | 1 pump; 2 pumps; 0; See notes |
| 5 | Plug_Screw_Feeder {2} | 1 pump; 2 pumps; 0; See notes |
| 6 | Hydrolyzer_Non-Driven_End {2} | 2 pumps; 0; See notes |
| 7 | Blow_Tank_Agitator {2} | 0; See notes |
| 8 | Screw_Press_Non-Driven_End {2} | 2 pumps; See notes |
| 9 | Screw_Press_Driven_End {2,3} | 2 pumps; 0; See notes |
| 10 | Reversing_Conveyor {2} | 0; See notes |
| 11 | CO2_Scrubber_Fan {2} | 0; See notes |
| 12 | Blow_Back_Dampner {4} | Grease added; 0 |
| 13 | Notes | *Desc.* |

1 Every 250 hours of operation.  
2 Every 750 hours of operation.  
3 Two bearings.  
4 As needed.  
