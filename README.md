# Attendance
An automated Biometric attendance system to keep records of student puctuality in class
An automated Biometric attendance system to keep records of student puctuality in class.
The application is written in C# communicating to MYSQL database using SecuGen Hamster plus USB fingerprint reader
The application can run on both 32 and 64 bit windows operating system.
///////////////
//////////////
To run the application plug in the USB SecuGen Hamster Plus fingerprint reader and lauch the application.
On Launch, to login to the admin panel use the login credentials
admin id = admin
password = admin123
/////////////
////////////
On login, the admin panel contain a navigation to either enroll student, mangage records, or register new class
To Enroll new student, click on the init button to initialize the fingerprint module, and fill the required detials before submiting to the database
///////////
//////////
To Mark attendance, click on the init button to initialize the fingerprint module
Enter Student matric number then click scan thumb to scan the thumb for matching
Click the Submit button to  mark attendance if matching is correct and if attendance hasn't been taken before.
