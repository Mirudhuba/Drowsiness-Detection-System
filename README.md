# Drowsiness-Detection-System

Nowadays drowsiness of drivers is one of the main reasons behind road accidents. Most people who travel long distances prefer to take night and early morning drives because that allows them to travel faster due to less traffic and helps to save a lot of time. It is natural for drivers who take long drives to doze off behind the steering wheel. Taxi drivers, bus drivers, truck drivers, and people traveling long-distance suffer from lack of sleep. Due to this, it becomes very dangerous to drive when feeling sleepy. The majority of accidents happen due to the drowsiness of drivers who travel during the night and early morning. This project intends to develop a computer vision system made with the help of OpenCV that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.

Eye aspect ratio (EAR) is a metric that measures the level of openness of the eye, based on the ratio of the distance between two points on the eye to the distance between two points on the eyebrow and the distance between two points on the eye. The EAR calculation involves identifying specific facial landmarks, typically the inner and outer corners of the eye and the 37 highest and lowest points of the eyebrow, and computing the distances between them. The ratio of the horizontal distance between the inner and outer corners of the eye to the vertical distance between the highest point of the eyebrow and the lowest point of the eyelid gives the EAR value. 

![image](https://github.com/Mirudhuba/Drowsiness-Detection-System/assets/96776766/d1a3753d-c31c-4746-9402-618c3d0f7df9)

EAR is calculated using the below formula,

![image](https://github.com/Mirudhuba/Drowsiness-Detection-System/assets/96776766/d080622e-d53c-4226-882e-6d9d8b166e99)

A higher EAR value indicates that the eye is more open, while a lower value indicates that the eye is more closed. An EAR threshold is set to 2 to detect if the driver is getting drowsy or falling asleep based on the decrease in the EAR value over time. 

![image](https://github.com/Mirudhuba/Drowsiness-Detection-System/assets/96776766/58e07d8c-5246-4b91-a6bd-12893e1685c8)


