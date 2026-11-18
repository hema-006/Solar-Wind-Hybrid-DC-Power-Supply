# Solar-Wind-Hybrid-DC-Power-Supply

This project models a battery-less hybrid renewable energy system combining a Solar PV array and a PMSG-based Wind Turbine in MATLAB/Simulink (R2024a).
Both sources step up voltage through dedicated DC-DC boost converters, with a Perturb & Observe (P&O) MPPT algorithm optimizing solar power extraction.
The outputs combine onto a common DC bus regulated at to power a direct DC load without battery storage.
To run the simulation, open the `.slx` file in MATLAB/Simulink with Simscape Electrical installed and click **Run** (`0.5 s` stop time).
