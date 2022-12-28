# SI-GuidedProject-416079-1670230970
Smart Attendance System using Face Recognition
Maintaining attendance is very important in all organizations for checking the performance of an Employee.
Every organization has its own method in this regard.
The traditional approach was marking attendance manually using the old paper or file-based approach and some have adopted methods of automatic
attendance using biometric techniques.
But in these methods employees have to wait for a long time in making a queue when they enter the office.

We are going to build this project using dlib which uses 128 point face detectors which outputs these 128 points 
from all the face and compares them with existing faces. This model uses the integrated webcam to capture the video frame.
The image of the person captured in the video frame is compared with the encodings of the faces of the pre-trained model. 
If there is a match, then the image of the employee is recognised and attendance is marked along with timestamp into a log file(excel file).  


