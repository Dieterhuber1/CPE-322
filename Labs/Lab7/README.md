# CPE 322
## Lab 7
### Introduction:
Through this lab I learned how to monitor and log CPU performance data such as CPU usage and available memory from my computer using Python. I then sent that data in real time to two platforms, ThingSpeak and Google Sheets.
## ThingSpeak
The first thing I did was create a new channel in ThingSpeak to get my Write API Key. Once I did this I was able to run the command python thingspeak_feed.py in the iot/lesson7 directory.
![thingspeak_feed.py output](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab7/python%20thingspeak_feed.py.png)
ThingSpeak then plotted the output data regarding my CPU usage and available memory.
![ThingSpeak output](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab7/ThingSpeak_output.png)
## Google Sheets
The first thing I did for this part of the labwas setup a Google Cloud project named cpudata. Then navigated to "APIs & Services > Library" and enabled Google Drive API and Google Sheets API. From there I went to the credentials tab, created a service account, then went under keys, created and downloaded the JSON key file.
![service account](https://github.com/Dieterhuber1/CPE-322/blob/main/Labs/Lab7/Service_account.png)
![key]()
