# AirQuality

======================================================
May SARS-CoV-2 be prevented by an indoor air monitoring smart data service?

Antonella Longo; Ali Aghazadeh Ardebili; Marco Zappatore; Divya Pragna Mulla
Dept. Engineering For Innovation, SyDA Lab, University of Salento, Lecce, Italy


Abstract:
The COVID-19 pandemic has shown the lack of tools for widely monitoring air quality in indoor public spaces, enabling data-driven decisions in everyday life, 
as they can play a significant role in abating the propagation of the SARS-CoV-2virus. Even actions as simple as opening doors and windows to ventilate rooms
are widely known to be highly effective, and they may be further beneficial if triggered depending on a proper evaluation of indoor air quality levels. However,
several online systems currently available on the Web mainly provide theoretical indoor air quality estimations without adequately exploiting IoT-supplied data
streams. To tackle such issues, this paper describes a smart service for alerting when the air quality conditions become critical for SARS-COV-2 propagation. 
It is based on a cyber-physical-social platform, enabled by IoT devices that monitor air quality components, elaborates over the collected samples to infer the
risk of SARS-COV-2 propagation. The result of the process alerts enabled users.
Published in: 2021 IEEE International Conferences on Internet of Things (iThings) and IEEE Green Computing & Communications (GreenCom) and IEEE Cyber, Physical 
& Social Computing (CPSCom) and IEEE Smart Data (SmartData) and IEEE Congress on Cybermatics (Cybermatics)



Date of Conference: 06-08 December 2021
Date Added to IEEE Xplore: 04 February 2022
ISBN Information:
Electronic ISBN:978-1-6654-1762-4
Print on Demand(PoD) ISBN:978-1-6654-1763-1
INSPEC Accession Number: 21646068
DOI: 10.1109/iThings-GreenCom-CPSCom-SmartData-Cybermatics53846.2021.00065
Publisher: IEEE
Conference Location: Melbourne, Australia



## How to run

1. Install the required libraries
`pip install missingno`
`pip install pydotplus`
`pip install sklearn`

Python version 3.9 recommended

2. Add the source file in the same directory of the notebook

**Note**: The source file must have the following columns: 
- Co2
- Humidity 
- Pm10 
- Pm25 
- Sound 
- Temperature 
- Tvoc

If it contains other columns, please remove them before running the script (or add the column names in the row
`data = df.drop(['Timestamp', 'Name', 'Position', 'Pm10', 'Pm25', 'Sound', 'Temperature', 'Tvoc'], axis='columns')` )


