# Solar Maximum Power Point (MPP) Controller

 The increasing demand for renewable energy
sources has highlighted the need for efficient photovoltaic
(PV) systems that can reliably harvest maximum energy
under varying environmental conditions. Traditional Maximum Power Point Tracking (MPPT) methods often suffer
from inefficiencies in tracking accuracy and response time,
particularly under dynamic irradiance and temperature
changes. Additionally, the variable output of PV arrays
poses challenges in delivering a stable and consistent power
supply for practical applications. This project addresses
these challenges by developing an advanced PV system
featuring a PI control-based MPPT algorithm and a DCDC boost converter, designed to enhance energy harvesting
efficiency and provide stable output. The system is modeled
and simulated in MATLAB (MATLAB), incorporating
real-time environmental data to ensure realistic and robust
performance validation, making it suitable for deployment
in real-world renewable energy scenarios.


## How to Run in Matlab
To execute the code and calculate the DC-DC converter ratings:

1. **Pre-requisites:**
   - MATLAB installed on your system.
   - Ensure that all required MATLAB toolboxes are installed.

2. **Steps to Execute:**
   - Open MATLAB.
   - Navigate to the folder containing the project files.
   - Run the file `DC_DC_con_Ratings_Calculations_Code.mat` by typing the following command in the MATLAB Command Window:
     ```matlab
     run('DC_DC_con_Ratings_Calculations_Code.mat')
     ```

3. **Output:**
   - The file calculates and outputs the required ratings for the DC-DC converter.
   - Results will be displayed in the MATLAB workspace and/or plotted as graphs.
## How to Run in Simulink
To execute the simulink model and observe the corresponding graphs:

1. **Pre-requisites:**
   - MATLAB Simulink installed on your system.
   - Ensure that all required MATLAB simulink toolboxes are installed.

2. **Steps to Execute for constant irradiance of 1000 signal "Test_Constant_1000"**
   - Open MATLAB simulink.
   - Navigate to the folder containing the project files.
   - Run the file `MPPT_Final_Working_Model.slx` by clicking run button
     

3. **Output:**
   - Check the graphs of PV Side and Output DC DC Converter.
     
4. **Steps to Execute for variable irradiance of 1000 signal "Test_Signal_MPPT"**
   - Open MATLAB simulink.
   - Navigate to the folder containing the project files.
   - Run the file `MPPT_Final_Working_Model.slx` by clicking run button
   - Make sure the input is connected to "Test_Signal_MPPT" signal.

5. **Output:**
   - Check the graphs of PV Side and Output DC DC Converter.

