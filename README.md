# Road-Safety-in-UK
<b>Analyzing Road Safety in UK</b>


The dataset for this project was taken from kaggle. The data was then imported to MySQL Workbench 8.0 CE with the DB name as help. The following 48 tables were imported:

(`1stpointofimpact`, `1stroadclass`, `2ndroadclass`, `accidents`, `accidentseverity`, `ageband`, `ageofcasualty`, `buspassenger`, `carpassenger`, `carriagewayhazards`, `casualtyclass`, `casualtyseverity`, `casualtytype`, `dayofweek`, `hitobjectincarriageway`, `hitobjectoffcarriageway`, `homeareatype`, `imddecile`, `journeypurpose`, `juncationcontrol`, `junctiondetail`, `junctionlocation`, `lightconditions`, `localauthoritydistrict`, `localauthorityhighway`, `pedcrosshuman`, `pedcrossphysical`, `pedlocation`, `pedmovement`, `pedroadmaintenanceworker`, `policeforce`, `policeofficerattend`, `roadsurface`, `roadtype`, `sexofcasualty`, `sexofdriver`, `skiddingandoverturning`, `specialconditionsatsite`, `towingandarticulation`, `urbanrural`, `vehiclelocation`, `vehiclemanoeuvre`, `vehiclepropulsioncode`, `vehicles`, `vehicletype`, `vehleavingcarriageway`, `wasvehiclelefthanddrive`, `weather`)


The above tables were imported using the LOAD INFILE command with double backslash "\\".

Example:

![image](https://user-images.githubusercontent.com/111077764/184465961-6873c8ef-f953-46d8-b8ac-fca532a840b8.png)

The answers to the following questions will be answered by using SQL queries:

1) Evaluating the median severity value of accidents caused by various Motorcycles.
2) Evaluating the Average Accident Severity and Total Accidents per Vehicle Type.
3) Calculating the Average Severity by vehicle type?
4) Calculating the Average Severity and Total Accidents by Motorcyclee.

The Answers to these questions are as follows:

1)

2) Average Accident Severity and Total Accidents per Vehicle Type:

<img width="698" alt="image" src="https://user-images.githubusercontent.com/111077764/184574274-a027da93-5d7b-4e7d-a76c-216d5b81f2a6.png">

Deserve it.

Push this main branch from atom.
