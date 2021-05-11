# Fall-detection-in-human-using-matlab

## INTRODUCTION:-
In this system we will try to build a system using matlab which can detect humans falling on the ground from a CCTV camera feed and so that we can limit the physical damage to the person by alerting the hospital authorities.

## OBJECTIVE:-
Elderly people tend to slip and fall in homes and remain unattended for a long time. If the affected person is not treated immediately, serious health issues including brain injuries occur. The proposed solution automatically detects humans falling, through cameras installed in homes, and sends notification to family members and hospital authorities. 

## OPERATIONAL DEFINITION:- 
The heart of this system is computer vision and edge detection algorithm.The video is processed frame by frame in the computer vision algorithm,it draw outline to the edge of the object,that traces the object movement.The algorithm detects the falling of human body by determining all the factors that include instantaneous speed,average speed,area change ,orientation change,average area change ,average orientation change.
When the object changes its speed ,orientation and area above a threshold value as determined in the algorithm,the body is concluded to be fall down.And sms is then send to the family member of the person who fell down,this is done using php CURL,and the hospital authorities are also,informed 

## APPLICATIONS:-
Help elderly peoples who are living alone.
It can help working parents who can not always look after their children.
References:
Cuong Nguyen The & Dmitry Shashev “MATEC Web of Conferences”  

# PPT
## https://docs.google.com/presentation/d/1knRGFWDc0ostNcmP3Mg8fZaZWPQROc8AiOKPS7ZI3IM/edit?usp=sharing
