Seung Yoo
seung.y.yoo@nasa.gov

CbA Aerodynamic Reference Data

*Committee provides reference data that is flight-test like by extracting noise
from flight tests and adding it to mean of several CFD that has been
performed. 

Point	Case 	Description				Mach	Alt(ft)	CL	Sideslip(deg)
1	A1	Cruise					0.85	35000	0.5	0
2	A2	Cruise - CL				0.85	35000	0.4	0
3	A3	Cruise + CL				0.85	35000	0.6	0
4	B	Cruise + Sideslip			0.85	35000	0.5	2
5	C	MMO					0.89	35000	0.46	0
6	D	Low Mach Low altitude			0.4	10000	0.5	0
7	E	Low Mach Low altitude + sideslip	0.4	10000	0.5	3

		
*beta convention
positive beta is such that aircraft's nose is pointing toward the left with
respect to the incoming flow, such that the incoming flow hits the aircraft on
the right hand side.

*data format
-each data file holds time history of all 64 pressure sensors
-first col is time stamp in seconds. 
-sensor location provided in file "Psensor_locations_xyz.csv". There are 64 pressure sensors 
-first row is header: t(sec) sensor_1 ... sensor_64
