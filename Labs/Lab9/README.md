# CPE 322
## Lab 9
### Introduction:
In this lab I got familiar with the file types .ying, .yang, and .uml. I also got familiar with the programs Pyang and PlantUML to practice converting file types and generating png's.

---

## Setup
The first thing I did was downloaded the intrusiondetection.yang into my demo folder from the Github repository. I than ran my powershell window as adminastrator to execute the following commands:
- 'pip install pyang'
![pip install pyang](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/pip%20install%20pyang.png)
- 'choco install plantuml'
![choco install plantuml](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/choco%20install%20plantuml.png)
## Pyang
To run Pyang I changed my directory to my demo folder and then executed the following commands:
- 'pyang -f yin -o intrusiondetection.yin intrusiondetection.yang'
- 'pyang -f uml -o intrusiondetection.uml intrusiondetection.yang'
![pyang command](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/pyang%20command.png)
### .yang
Shown below is the .yang file that was generated:
![.yang1](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/.yang1.png)
![.yang2](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/.yang2.png)
![.yang3](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/.yang3.png)
### .yin
Shown below is the .yin file that was generated:
![.yin1](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/.yin1.png)
![.yin2](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/.yin2.png)
![.yin3](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/.yin3.png)
### .uml
Shown below is the .uml file that was generated:
![.uml](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/.uml1.png)
## PlantUML
In order to execute the final part of the lab I used the command: plantuml intrusiondetection.uml. The following shows the generated png file:
![png](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab9/intrusiondetection.png)


