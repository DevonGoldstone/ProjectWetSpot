#	Project Wet Spot Functional Design Specification
![alt text](https://ezpetcareful.com/wp-content/uploads/2017/04/Best_LED_Lights_for_Reef_Tank.jpg "Reef Tank")
## 1.  Introduction
### 1.1.	Overview
This document is intended to expand on the Customer Requirements Specification in order to identify the 'Project Wet Spot' Functional Requirements
###  1.2 Scope of document
This document lists the required functionality for 'Project Wet Spot' as well as to capture the technology and means to be used in realising this functionality. 
###  1.3 Reference documents
The documents listed in the Customer Requirements Specification have been used as reference materials for this specification. 
Where information has been gathered from external sources, this will be cited in the text
###	1.4 Constraints, Assumptions, and Dependencies
####  1.4.1 Constraints
The System will work with an Innovative Marine Fusion Nano 20 fishtank and TMC Aquarium V2 power pump 800.
For safety purposes, wherever possible hardware should be DC supplied
####  1.4.2 Assumptions

####  1.4.1 Dependencies

###	1.5 Required product functionality
Means of meeting the customer requirements specification have been collated and listed in the table below (categorised by which CRS requirement they meet: 

##  Monitoring Functionality
| Priority |	Functionality	|	Applicable requirement(s)	|
|	:-------------: |	:------------- |	:------------- |
|	 High | Light monitor (Lux/Kelvin/PAR)	|  Ease, diagnostics |
|	 Low | Pump monitoring | Ease, diagnostics |
|	 Low | Autofeeder monitoring | Ease, diagnostics |
|	 Low |	Ammonia monitoring	(0 ppm)  |	Ease, diagnostics	|
|	 Low |	ATO monitor	|	Ease, diagnostics	|
|	 Low |	pH monitoring	| Ease, diagnostics |
|	 High |	Temperature monitoring	(  27 - 29°C) |	 Ease, diagnostics |
|	 Low |	Salinity monitoring (35 ppt)	|	 Ease, diagnostics |
|	 Low |	ORP monitoring	|	 Ease, diagnostics |  
|	 Low |	Power monitoring  |	 Ease, diagnostics |
|	 Low | Calcium monitoring (400 - 500 ppm) |	 Ease, diagnostics |
|	 Low |	Carbonate Alkalinity (3.2 - 4.5 mEq/L) |	 Ease, diagnostics |
|	 Low | Carbonic Hardness (7 - 12 dKH) |	 Ease, diagnostics |
|	 Low |	Phosphate (>0.3 ppm) |	 Ease, diagnostics |
|	 Low | Nitrate (>10 ppm) |	 Ease, diagnostics |
|	 Low | Magnesium (ppm) |	 Ease, diagnostics |
|	 Low | Ammonia (ppm) |	 Ease, diagnostics |
|	 Low | Nitrite (0 ppm) |	 Ease, diagnostics |

Consider also: Strontium, Iodine, Bromide, Flouride and vanadium

##  Control Functionality
|	 Priority |	Functionality	|	Target Level  | Applicable requirement(s)	|
|	:-------------: |	:------------- |	:------------- |	:------------- |
|	 Low |	Manual and automated autofeeder control	| TBC |	Supports life, maintenance free operation, growth, longevity, ease	|       
|	 High |	Manual and automated lighting control	| TBC |	Supports life, maintenance free operation, growth, longevity, ease	|
|	 Low |	Manual and automated return pump control	|	TBC | Supports life, maintenance free operation, growth, longevity, ease	|
|	 Low |	Manual and automated ATO control	|	1.023 - 1.027 / 35 ppt | Supports life, maintenance free operation, growth, longevity, ease	|
|	 Low |	Manual and automated pH control  | 	8.2 - 8.4     |	Supports life, maintenance free operation, growth, longevity, ease	|
|	 High |	Manual and automated (PID) Heater control	|  27 - 29°C | Supports life, maintenance free operation, growth, longevity, ease	|
|	 Low |	Manual and automated ORP cotrol	| TBC |	Supports life, maintenance free operation, growth, longevity, ease	|
|	 Low |	Manual and automated 24V DC out power control	|  TBC |	Supports life, maintenance free operation, growth, longevity, ease	|
|	 Low |	Manual and automated relay switched mains power control	|  TBC |	Supports life, maintenance free operation, growth, longevity, ease	|
|	 Low |	Manual and automated calcium control	| 400 ppm - 450 ppm |	Supports life, maintenance free operation, growth, longevity, ease	|
|	 Low |	Manual and automated Carbonate Alkalinity / Carbonic Hardness control	| 3.2 - 4.5 mEq/L / 7 - 12 dKH |	Supports life, maintenance free operation, growth, longevity, ease	|
|	 Low |	Manual and automated Phosphate control	| 0.2 - 0.8 ppm |	Supports life, maintenance free operation, growth, longevity, ease	|
|	 Low |	Manual and automated Magnesium control	| 1250 - 1400 ppm |	Supports life, maintenance free operation, growth, longevity, ease	|

Consider also: Strontium, Iodine, Bromide, Flouride and vanadium
***
##  General Functionality
|	 Priority |	Functionality	|	Applicable requirement(s)	|
|	:-------------: |	:------------- |	:------------- |
|	 Low | Mains powered | Maintenane free operation |
|	 Low |	24Hr UPS  | Failure, Supports Life |
|	 Low |	Ethernet	|	 Remote Control, Access |
|	 Low |	Wireless	|	Remote Control, Access |
|	 Low |	ICE Actions for system and module failure	|	Failure, Supports Life, Planning |
|	 Low |	Can operate without internet access	|		Failure, Supports Life  |
|	 Low | Monitored item status indication, associated alarms	and email alerts  | Ease, Diagnostics, Style |
|	 Low |	Probe calibration	|	Cost, Ease  |
|	 Low |	Monitored item graphing	|	Diagnostics, Style |
|	 Low |	Tracking of manual test results, maintenance, purchases, observations etc	|	Diagnostics, Ease	|
|	 Low | Rolling scheduling of controlled fuctions | Planning  | Maintenance free operation  | Ease  |
|	 Low | Reactive control functionality  | Maintenance free operation, failure |
***
## MECHANICAL SPECIFICATION
|	 Priority |	Description	|	Applicable requirement(s)	|
|	:-------------: |	:------------- |	:------------- |
|	 Low | System should fit neatly on a shelf beneath fishtank ~6" * 3" * 3" | Size |
|	 Low | System should be IP64 rated | Water protection, Connections |
|	 Low | System should be physically robust to survive a fall or bump  | Strength  |
|	 Low | All system connections should be clearly identified, unique plugs, support IP rating, be physically robust| Water protection, Strength, Connections |
|	 Low | Incorrect connection of plugs should not result in system damage  | Electrical protection, Connections, Ease, Cost  |
|	 Low | User interface should be intuative and accessible so that an inexperienced user could operate with minimal/ no guidance | Style |
***
Must be able to control up to 4 power heads (DC or AC)
Up to 2 heaters max 300 watt, AC, Max current required: 2.6A (round up to 3A for margin)
1 air pump (12V)
1 return pump (24V 1.1A)
2 media reactors (24V max current required: 2.4A)
4xdoser for all minerals (12V 1A)
1 protein skimmer (24V 1.1A)
fans x2 (12V 1.7W)
ato (24V 1.1A)
##  2 System Power
![alt text](https://drive.google.com/open?id=1aqrVxX16xwGvS0-2V9eq5WB-cfVHklIj "Top Level Power Schematic")
