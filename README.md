# MARS
## Aim Shooting Bot

The project was approached in many different ways both in terms of mechanical and electronic aspects.
Many different codes for the same are given and the ones named final are the ones which were finally implemented.
The alternatives also work well but were discarded given the resources.

### Images 

### Abstract:
The project basically aims and shoots person in real time.

### Motivation:


### Mechanical Aspect:


### Electronic Aspect:
It uses tensorflow object-detection API to do the same.So it is easily possible to aim for 100 different classes as given in the API. It makes the model robust to changes as per the type of object which it should aim irrespective of the surrounding.

The electronic design uses arduino mega for controlling. One motor was used for the rotation and the other for the reload mechanism. For rotation Stepper was used with PID control. For reloading a 900rpm dc motor was used. Two motor drivers were used each for one motor.

Apart from that as all the image processing was done on Laptop a USB-TTL converter was used and attached to arduino for proper communication.

### Cost Structure:

### Applications:
It can be deployed at larger scales for border security that is to say in defense applications. As the model is robust to surroundings and can detect any out of 100 different classes it makes it better for use in Defense applications.

### Limitations:
The only limitation is that it has no optical locking mechanism that is to say that it doesnt work properly if it has more than one object of interest in its frame. 

### Future Improvements:
Better tuning of the PID.
Using Optical Flow for target locking.
Better mechanical design to make it more appealing.

### Team Members:
Abhishek Agarwal
Aditya Kanfade
Aditya Raj
Jatin Varshney

### Mentors:
Prashant

References:
Tensorflow object Detection-API
https://www.youtube.com/playlist?list=PLQVvvaa0QuDcNK5GeCQnxYnSSaar2tpku

Sample model for mechanical structure.
https://www.youtube.com/watch?v=HoRPWUl_sF8

