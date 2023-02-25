# 👣 New Balance

## Project Title
__*: IoT Device and Visualizing Application for Monitoring the Running Gait*__

Our project suggests a mobile application that monitors running gait using IoT.
We utilized IMU-6050 sensors and a pressure sensor to measure the angle of the foot and identify different strike types.

## Group Members

<div align="center">
  
|[Jihyeon Yun](https://github.com/jhYun505)|[Hojeong Eom](https://github.com/DobiIsFree)|[Minju Kim](https://github.com/mjkim1019)|[Hyejin Kim](https://github.com/WZNT-KimHyeJin)|[Suyoung Lee](https://github.com/vime-ux)|[Nicole Hornbrook](https://github.com/nicole-janae)
|:----:|:----:|:----:|:----:|:----:|:----:|
|Chungnam National Univ.|Chungnam National Univ.|Soongsil Univ.|Chungnam National Univ.|Chungnam National Univ.| Purdue Univ.
|IoT|IoT|Mobile|Back-end|Back-end|Software|
|<img src="https://avatars.githubusercontent.com/u/81208791?v=4" width="150">|<img src="https://avatars.githubusercontent.com/u/52994616?v=4" width="150">|<img src="https://avatars.githubusercontent.com/u/50831854?v=4" width="185">|<img src="https://avatars.githubusercontent.com/u/62338783?v=4" width="150">|<img src ="https://avatars.githubusercontent.com/u/84793929?v=4" width="150">|
</div>

## Result of this Project
### Device
<img width="1169" alt="Final Prototypw" src="https://user-images.githubusercontent.com/81208791/221383046-f7cb41e9-c53b-458d-a767-4d06da0a29b1.png">

### Application
<img src="https://user-images.githubusercontent.com/50831854/216420506-f7569220-8355-4af4-a86b-4119e5426d93.png" width=70% align="center">

## Goal of NewBalance
 Our goal is to make an application that monitors the user's running gait. We will provide running information such as distance, average pace, and total time of the run, much like other existing running applications. Unlike other applications, however, we will provide the measured foot angle and the location of the first point of contact. After the IMU sensors and pressure sensor measure the user's run, the data will be sent to the server. After that, the server will processes and analyze the data. Once this process is over, the app will visualize this data to help the user monitor his/her running gait.

## Why we chose this topic
1. Growth potential of IoT usage in healthcare is exponentially increasing
2. Current lack of research on running gait monitoring & analysis
3. The reoccuring rate of injury from running is high

## Previous Research Problem
 Previous studies were costly and restricted to experimental environments only. Most existing related research used motion capture; meaning, they used many cameras and a treadmill to monitor their runners' gait. Additionally, there are hardly any running gait monitoring applications for real users.

## Our Novelty

1. **Cost Effective**
    - Using sensors is more cost effective over using motion capture
    - Sensors have similar accuracy to motion capture
    
2. **Free from Environmental Constraints**
    - Studies we've previously mentioned were limited to experimental conditions indoors
    - In this study, all the experiments are conducted in an actual running environment
    
3. **User-friendly**
    - It can be used in sports training
    - We clearly vizualize statistical data so users can easily understand their personal running information


## Expected Outcome
1. **Provide personal Statistical Data**

This application provides personal statistical data to the user. Once the user finishes their run, he/she reports their emotional and physical state by responding to the question, 'How was your run?'.

2. **Help prevent running injuries**

Runners can choose to use the data to self-correct their running posture or utilize it as reference material for a consultation with an expert (that could include a doctor, physical therapist, or sports trainer). So, this app could help prevent running injuries. 

## Activity Diagram
 
<left><img src = "https://user-images.githubusercontent.com/50831854/216443390-dc15cccd-437e-44f5-a234-485c4e17671a.png" width = "800" >


## System Flowchart

<left><img src = "https://user-images.githubusercontent.com/84793929/220672865-f103320e-877e-4163-83b9-9c2a57957db8.png" width = "800" >

## Enviroment settings

  ### Google Cloud Platform
    ✔️ 4 vCPU
    ✔️ 4GB memory
    ✔️ 10GB distributed
  
  #### ThingsBoard
 
    ✔️ OS: Ubuntu Desktop 20.04 LTS
    
    ✔️ ThingsBoard Version: thingsboard-3.4.3
    
    ✔️ Specific Settings:
       - ThingsBoard Queue Service: In memory (built in, default)
       - Dependency: openjdk-11-jdk, postgresql-12
  
<div>
<img src="https://github.com/tandpfun/skill-icons/raw/main/icons/Flutter-Dark.svg" width=20 align="center"/> 
<b>Flutter</b> 
</div>

</br>

```
Flutter: 3.7.1
Dart: 2.19.1
DevTools: 2.20.1
Xcode: 14.1
Android Studio: 2022.1
Android SDK: 33.0.0
VS Code: 1.73.1
```

