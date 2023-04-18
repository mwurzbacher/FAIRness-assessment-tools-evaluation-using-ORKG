# FAIRness-assessment-tools-evaluation-using-ORKG
Code for evaluating automated FAIRness assessment tools using the Open Research Knowledge Graph (ORKG) as input data

## FAIR-Checker notebook
Please note: the FAIR-Checker API responds very slowly and not always with a 200 response. Hence, I have disabled the cells that actually communicate with the FAIR-Checker API. If you want to re-run the assessment by FAIR-Checker you need to enable these cells. To do this, you need to remove the first line (that says `%%script false`) from those cells. As a heads up: It can take several days to run this notebook completely when these cells are enabled. If you don't have that amount of time, you can use the csv assessments found in the "assessed_data" folder and keep the respective cells disabled. 

FAIR-Checker API: https://fair-checker.france-bioinformatique.fr/swagger

## F-UJI notebook
Please note: F-UJI does have a public API, however, for larger amounts of data, they request to use a local server instance. Thus, this notebook refers to a local server instance and cannot just be used on your system without (minor) adaptations, i.e. setting up a local server instance and adjusting the credentials in the notebook to refer to this instance

F-UJI API: http://168.119.191.2:1071/fuji/api/v1/ui/
F-UJI source code: https://github.com/pangaea-data-publisher/fuji