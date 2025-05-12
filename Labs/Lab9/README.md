# CPE 322
## Lab 9
### Introduction:
In this lab I got familiar with the file types .ying, .yang, and .uml. I also got familiar with the programs Pyang and PlantUML to practice converting file types and generating png's.

---

## Setup
The first thing I did was downloaded the intrusiondetection.yang into my demo folder from the Github repository. I than ran my powershell window as adminastrator to execute the following commands:
- 'pip install pyang'
![pip install pyang]()
- 'choco install plantuml'
![choco install plantuml]()
## Pyang
To run Pyang I changed my directory to my demo folder and then executed the following commands:
- 'pyang -f yin -o intrusiondetection.yin intrusiondetection.yang'
- 'pyang -f uml -o intrusiondetection.uml intrusiondetection.yang'
![pyang command]()
### .yang
Shown below is the .yang file that was generated:
![.yang]()
### .yin
Shown below is the .yin file that was generated:
![.yin]()
### .uml
Shown below is the .uml file that was generated:
![.uml]()
## PlantUML
In order to execute the final part of the lab I used the command: plantuml intrusiondetection.uml. The following shows the generated png file:
![png]()


