# College-ERP
A college management system built using Django framework. It is designed for interactions between students and teachers. Features include attendance, marks and time table.

## Installation

Python and Django are required for the code to run

```bash
pip install django
```

## Usage

Go to the College-ERP folder and run

```bash
python manage.py runserver
```

Then go to the browser and enter the url **http://127.0.0.1:8000/**


## Login

The login page is common for students and teachers.  
The username is their name and password for everyone is 'project123'.  

Example usernames:  
student- 'samarth'  
teacher- 'trisila'

All usernames are given at the end.

You can access the django admin page at **http://127.0.0.1:8000/admin** and login with username 'Shishir' and password 'Project@123'

Also a new admin user can be created using

```bash
python manage.py createsuperuser
```

## Users

New students and teachers can be added through the admin page. A new user needs to be created for each. 

The admin page is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.

**For more details regarding the system and features please refer the reports included.**

## Update (29/11/2020)

Added method to reset attendance time range in Django Admin page.

![alt_text](https://i.imgur.com/0xOWmUZ.png)

This is present in Django Admin -> Attendance (http://127.0.0.1:8000/admin/info/attendanceclass/).  
Start Date: Start Date of Attendance period  
End Date: End Date of Attendance period

This will delete all present attendance data and create new attendance objects for the given time range. 

## Screenshots

### Teacher Page

![alt text](https://imgur.com/pMAoEbG.png)

![alt text](https://imgur.com/ZiQ3RRA.png)

![alt text](https://imgur.com/i025CJW.png)

![alt text](https://imgur.com/HQlLYmC.png)

![alt text](https://imgur.com/j6RyBmU.png)

![alt text](https://imgur.com/xIKEMvQ.png)

![alt text](https://imgur.com/4Rl7Fpv.png)

### Student Page

![alt text](https://imgur.com/isL9cjz.png)

![alt text](https://imgur.com/5pzl7m3.png)

![alt text](https://imgur.com/7zWhHZx.png)

![alt text](https://imgur.com/fu7gxk8.png)

![alt text](https://imgur.com/NZqU268.png)

### Admin Page

![alt text](https://imgur.com/sDvDc9N.png)

![alt text](https://imgur.com/tMKWx6f.png)

![alt text](https://imgur.com/PvCsNeB.png)

## List of usernames

Username | Admin
---------|---------
Shishir	| True
aayan | False
abby | False
amc	| False
anilkumar | False
anna | False
anudeep | False
ariella	| False
ashleigh | False
axel | False
bodhi | False
boss | False
brooklyn | False
dakshath | False
dennis | False
dustin | False
eliza | False
envteacher | False
farhan | False
gary | False
guru | False
hugo | False
jensen | False
jillian	| False
joel | False
joy	| False
kaya | False
keenan | False
kirstie	| False
latisha	| False
lindsay	| False
lorcan	| False
maci | False
maison | False
manimala | False
manisha	| False
manjula	| False
manjunath | False
martin | False
ned | False
nihal | False
nikhil | False
osama | False
paisley	| False
rachel | False
rajat | False
renu | False
rian | False
ronaldo	| False
roopamala | False
samantha | False
samarth	| False
sapphire | False
shahid | False
shalini	| False
shanice	| False
sheela	| False
shravan	| False
sol	| False
srinath	| False
steven | False
tayla | False
tejus | False
trisila	| False
usha | False
varsha | False
vijeth | False
zara | False