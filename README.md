# KUL Datathon 2024

![Alt text](img/title.png)


### Introduction
Optimize the placement of AEDs is crucial to save lives. In this project, we aim to propose a AED allocation strategy based on the analysis of the accessibility of AEDs and medical transport (Ambulance, MUG and PIT), and historical data of cardiac arrest intervention in Belgium. We calculate the areas where medical transport and AED are not accessible within specific time, and visualize the "void" areas, and based on the histrical data and accessibility of AED, we propose AED placement strategy in a specific area.

### Folder Structure
1. `01_Dataset/` <br>
    Original dataset is provided by the organizer. <br>
    (URL: https://kul-datathon-jobfair.netlify.app/)
    - `01_Add_coordinate/` : Add coordinate of AED, MUG and PIT dataset using Google Map API.
    - `02_cardiac_intervention/` : Aggregate cardiac arrest intervention data from original datasets.
    - `03_population_density_dataset/` : AED dataset

2. `02_Driving times/` <br>
    Calculate areas where medical transport such as ambulances, MUG and PIT can reach within specific time by car. It uses HERE Maps API.
3. `03_WalkingTime_AED/` <br>
    Calculate areas where people can reach within specific time to AED by walking. It uses HERE Maps API.
4. `04_Visualization_Dash/` <br>
    Visualization of the "void" areas where medical transport and AED are not accessible within specific time. This visualization is used for creating a proposal for strategic AED placement. This folder is based on Dash framework, and can be deployed as a web application.

5. `05_Presentation/` <br>
    Presentation file for the pitch on the datathon.
