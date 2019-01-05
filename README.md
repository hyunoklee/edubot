## Description
Edubot Project.  
실물과 연동되는 Code 들어있지 않고 오직 simulation code만 들어있습니다.   
<img src="/picture/1.png" width="70%" height="70%">      
터틀봇3 도 작지만 해당 봇은 별도 SBC를 사용하지 않고 MCU만 으로 구성될 예정이라 더 작습니다. ^^;;    
<img src="/picture/2.png" width="70%" height="70%">      

## Run

* run empty world   
```bash
$roscore
$roslaunch edubot_gazebo edubot_empty_world.launch
$roslaunch edubot_teleop edubot_teleop_key.launch
```
* run navigation   
라이다를 사용하지 않고 front distance sensor 만 있어서 터틀봇3 대비 navigation package 기능이 약합니다 .  
```bash
$roscore
$roslaunch edubot_gazebo edubot_wall_world.launch
$roslaunch edubot_navigation edubot_navigation.launch
```
Click image to link to YouTube video.  
[![Video Label](http://img.youtube.com/vi/V3V0Liitapg/0.jpg)](https://youtu.be/V3V0Liitapg?t=0s)
