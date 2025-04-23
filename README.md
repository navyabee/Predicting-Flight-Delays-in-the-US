# Predicting-Flight-Delays-in-the-US
CSE6242 Spring 2025
Team Members: Navya Bingi, Andrew Guerrero, Agha Yusuf Khan, Zone Li, Ariana Richardson & Tyra Silaphet


Our project composes of a classification model to predict the potential risk of a flight delay from either the arrival or departure perspective. We use on-time performance data provided from the Bureau of Transportation alongside local METAR data to study delay phenomenon at ATL Hartsfield Jackson Airport between the years 2022-2024.

Full Dashboard: https://public.tableau.com/views/FlightDelayDashboard-4_20/DepartureDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

DEMO Video: https://youtu.be/A3SqsYvynk0

See below for Software Requirements, Demo Instructions, and Directory Navigation.
___________________________________________________________________________________________________________
Required Software: 

Licensed Tableau Desktop - https://www.tableau.com/trial/tableau-software

Python Jupyter Notebook Editor/IDE - (we used VSCODE: for main installations) - https://code.visualstudio.com/ 
_____________________________________________________________________________________________________________

DEMO Instructions- 

Step 1: Read Instructions in README.txt file -> already completed!

Step 2: Ensure require software is installed.  

**Self Guided Dashboard Setup**: else skip to Step 5

Step 3: Go to CODE -> DEMO - Snapshot Experiment -> DEMO_snapshot_exp.ipynb (Jupyter Notebook); install listed python packages (dependencies).

Note: By default, the DEMO will use Q1 2022 data (as shown in .twbx file and .ipynb start/end parameters); in video, Yusuf uses full project dataset for his demonstration. You may adjust start and end parameters within constraints of 2022-end of 2024. 

Step 4: Open Tableau.twb file of the dashboard. Click past any error messages and reconnect broken file path connections if any. The required data sources should be in same DEMO folder (ensure correct file connections). Check both the Departures Dashboard and Arrivals Dashboard components in lower tabs (go all the way right). Once done, select presentation view for best results.  

**Pre-configured DEMO Dashboard Setup**:

Step 5: Simply click on the .twbx dashboard version to be greeted with a pre-configured setup. This snapshot is of Q1 2022. For full dashboard viewing (pre-configured), see web-based Tableau Public version above. 

___________________________________________________________________________________________________

**Directory Structure**

DOC 
-- Written Deliverables (Poster, Report)
-- Product Feedback - Experiment -> .csv of survey respondents' feedback

CODE 
-- DEMO Folder (DEMO/Snapshot Version - Experiment) -> see above!
-- Code Folder (Full Model Code) -- use dva_modeling_final.ipynb -> .parquet are the input files and models are found in .joblib (can skip model training via those files)
-- Tableau Viz Folder (Full Dashboard Version) - can follow steps 3-4 of DEMO instructions for full viz setup (albeit in Tableau Viz Folder). 
