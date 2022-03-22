# ServicesDemo
This project is helpful to learn services concepts

<b>Types of services</b>
1)Schedules service.<br>
<br>Replacement of AlarmManager:it is time specific not condition specific 

<br>Sync data with server only when connection to wifi
<br>Start downloading the file only when device plugged in.


2)Started Service.
it is started from android components(Activity/Receiver/Provider/Service)
startservice()
stopservice()
stopself()


3)Bounded Service.
it is a type of startservice 
bindService()
As per the android component destroyed then service will destroyed.


4)Intent Service.
Runs on its seperate Background Thread 
Destroyed when the task finishes
Broadcast receiver is used to communicate with UI.




<b>Service</b><br>
A service is a component that runs in the background to perform long-running it has no UI
<br>

1) Bounded service(bound with activity or any other anroid components)<br>
2) Background service(does not notify user)<br>
3) Forground service(notify user though ongoing notifications)<br>
