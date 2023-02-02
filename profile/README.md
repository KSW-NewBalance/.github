# 👣 New Balance

## Project Title
__*: IoT Device and Visualizing Application for Monitoring Running Gait*__

Our project suggests mobile application that monitors running gait by using IoT.
We utilized IMU-6050 sensors and pressure sensor to measure angle of the foot and identify strike type people have.

## Group Members

<div align="center">
  
|[Jihyeon Yun](https://github.com/jhYun505)|[Hojeong Eom](https://github.com/DobiIsFree)|[Minju Kim](https://github.com/mjkim1019)|[Hyejin Kim](https://github.com/WZNT-KimHyeJin)|[Suyoung Lee](https://github.com/vime-ux)|Nicole Hornbrook
|:----:|:----:|:----:|:----:|:----:|:----:|
|Chungnam National Univ.|Chungnam National Univ.|Soongsil Univ.|Chungnam National Univ.|Chungnam National Univ.| Purdue Univ.
|IoT|IoT|Mobile|Back-end|Back-end|Software|
|<img src="https://avatars.githubusercontent.com/u/81208791?v=4" width="150">|<img src="https://avatars.githubusercontent.com/u/52994616?v=4" width="150">|<img src="https://avatars.githubusercontent.com/u/50831854?v=4" width="185">|<img src="https://avatars.githubusercontent.com/u/62338783?v=4" width="150">|<img src ="https://avatars.githubusercontent.com/u/84793929?v=4" width="150">|
</div>

## Result of this Project
<img src="https://user-images.githubusercontent.com/50831854/216420506-f7569220-8355-4af4-a86b-4119e5426d93.png" width=70% align="center">

## Goal of NewBalance
 We're goal is to make the application that monitors the user's running gait. We will provide running imformation such as distance, average pace, and total like other existing running applications. But why we're project is special is that we will provide the measured foot angle and the first position to step on. After IMU sensors and pressure sensor measure the user's running, the data will send to the server. After that, the server processes and analyze these data. All these process is over, app visualizes these data to help the user keep monitoring your running gait.

## Why we choose this topic
1. Potential of growth of IoT usage in healthcare is exponentially increasing
2. Current lack of research on running gait monitoring & analysis
3. The reoccuring rate of injury by running is high

## Previous Research Problem
 From research, there were problems of high cost and restrictions on experimental environment. Most of the paper that analyzed running posture researched using the motion capture method. So they used a bunch of camera to monitor people's gait and treadmill for experimental tool.
 Additionally, there is little running gait monitoring application for actual user.

## Our Novelty

1. **Cost Effective**
    - Using sensors is cost effective than using motion capture method
    - Even it also have an similar accuracy as motion capture method 
    
2. **Free from Environmental Constraints**
    - Studies we've mentioned had limitations in conducting experiments indoors
    - In this study, all the experiments are conducted against the background of the actual running environment
    
3. **User-friendly**
    - It can be used in practice
    - We shows statistical data with visualization, so users can easily understand their personal data


## Expected Outcome
1. **Provide personal Statistical Data**

This application provides persoanl statistical data to user. Once the user finishes their run, he/she reports their emotional and physical state by responding to the question, 'How was your run?'.

2. **Help prevent running injuries**

Runners can choose to use the data to self-correct their running posture or utilize it as reference material for a consultation with an expert (that could include a doctor, physical therapist, or sports trainer). So it could help prevent running injuries. 

## Activity Diagram
 
<left><img src = "https://user-images.githubusercontent.com/50831854/216443390-dc15cccd-437e-44f5-a234-485c4e17671a.png" width = "800" >

## Enviroment settings
  
  #### ThingsBoard
 
    ✔️ OS: Ubuntu Desktop 21.10
    
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

### Docker
<img src="https://github.com/tandpfun/skill-icons/raw/main/icons/Docker.svg" width=30 />

<aside>
✏️

</aside>
