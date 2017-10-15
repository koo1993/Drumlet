# Drumlet
Drumlet is a cost-efficient method for drummers to play the drums anywhere, anytime.

## Hackers
[https://github.com/fustilio](Francis Lee)
[https://github.com/Jeremylsw](Jeremy Long)
[https://github.com/koo1993](Wayne Koo)
[https://github.com/shanwpf](Shannon Wong)


## YouTube Demo Link
[https://www.youtube.com/watch?v=5jdy1lruVHc&feature=youtu.be](Click Here)

## Inspiration 
When brainstorming a hack to work on, a groupmate played a video of a [https://www.youtube.com/watch?v=A_kloG2Z7tU](comedy) scene of Rowan Atkinson playing the air drum. Given the limited resources we have (Two Arduinos and a number of sensors which can be only counted with one hand), we then decided to work on this hack to make an air drum with whatever we can find. Although there are air drums in the market today, a pair of air drums costs about 157 Euros which is about [http://aerodrums.com/shop-policies/](250 SGD). Our main focus was then to make a pair of air drums which was cost efficient such that individuals who would like to get the feel of playing the drums without spending a bomb can get to enjoy the drumming experience.

## What It Does
A Drumlet is an air drum that is able to play eight unique drum sounds

## How We Built It
Each Drumlet is connected to an Arduino, a button/joystick, and accelerometer (MPU 6050). By making use of yaw pitch values, we are able to make an air drum that has 8 unique sounds. Four on each side, two of which can be played by default and an additional two sounds can be toggled by the button/joystick on the handle of the drumstick. Sounds are played based on the Drumlet's horizontal position (yaw). A registered hit is based on the rate of change of pitch. 

## Challenges We Ran Into
Initially, we intended to integrate the drum set onto an Arduino but this proved to be difficult as more inputs to the Arduino resulted in frequent crashes. To alleviate this problem, we decided to split each drumstick up and built it on an Arduino each.

## Accomplishments That We're Proud Of
Being able to make it work!

## What we learned
Technical skills, debugging hardware problems are a pain and sleep is for the weak

## What's next for Drumlet
Making it more cost-efficient, wireless, portable, aesthetic.

## Acknowledgements
[https://diyhacking.com/arduino-mpu-6050-imu-sensor-tutorial/](MPU 6050 Tutorial By Arvind Sanjeev)

