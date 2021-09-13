
Systec Summer School: Module 3 -- Power Quality 
----

## UPDATE: 
Presentation in the following [LINK](https://github.com/vitormorais/SummerSchool_PowerQuality/raw/main/Systec_SummerSchool_2021_PQIssues.pdf)

---
## DESCRIPTION

This repository comprises two important folders: **\1. scripts** and **\2. data** to support the module

### Current Development Version
There are two options:
1. Clone the repository from GitHub.
2. Download a ZIP file of the repository from GitHub.

### System Requirements
*   MATLAB version 9.4 (R2021a) or later
*   (older versions might not be compatible)

### Usage
1. Open the matlab with the workspace in the cloned repository;
2. Run the file **a.load_data.mlx**
3. Run the script **b.process_voltage_grid.mlx** to analyse the grid voltage (DEMO1);
4. Run the script **c.process_current_1ph.mlx** to analyse the grid currents (DEMO2);
5. Run the script **d.process_power_3p.mlx** to analyse the generated 3p system (DEMO3);

## Data & .csv files

#### Demo 1
|Filename| Description  |
|--|--|
| demo1\meas11.csv | grid voltage measurement without load |
| demo1\meas12.csv | grid voltage measurement with heater |
| demo1\meas13.csv | grid voltage measurement with heater + bridge rectifier with LC filter |
| demo1\meas14.csv | grid voltage measurement with bridge rectifier C filter |

#### Demo 2
|Filename| Description  |
|--|--|
| demo2\meas21.csv | grid current measurement with heater |
| demo2\meas22.csv | grid current measurement with heater + bridge rectifier with LC filter |
| demo2\meas23.csv | grid current measurement with heater + bridge rectifier with C filter |
| demo2\meas24.csv | grid current measurement with bridge rectifier with LC filter |
| demo2\meas25.csv | grid current measurement with bridge rectifier with C filter |

#### Demo 3
|Filename| Description  |
|--|--|
| demo3\meas31.csv | three-phase generated grid: no load (100 Hz) |
| demo3\meas32.csv | three-phase generated grid: resistive + inductive load (75 Hz) |
| demo3\meas33.csv | three-phase generated grid: non-linear 3p bridge rectifier load (75 Hz) |
 


## !!!!  CHALLENGE  !!!!

#### Grid voltage analysis
*  get RMS value and check if complies w/ standards
*  get THD value and check if complies w/ standards
*  perform spectrum analysis
*  
#### Grid current analysis
*  perform a comparison analysis between different loads;

#### Three-phase analysis
* get the impedance value of the load.

#### Check the deliverable template in:
[..\1. scripts\template.mlx](https://github.com/vitormorais/SummerSchool_PowerQuality/raw/main/1.%20scripts/template.mlx)


----
### Documentation and Manuals
Under construction

