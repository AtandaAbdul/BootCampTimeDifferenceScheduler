# BootCampTimeDifferenceScheduler
The app, entirely written in python makes use of python containers which hold bootcamp schedules, countries,regions and their respective time zones.

The app was developed to help solve the time difference issues that occur between international students who miss OneCampus bootcamps that are held in EST due to various time differences of the respective students.

APP SPECIFICATIONS

0. Can calculate the EST equivalent time of any specified country in real time.
1. Can tell the current time in any country specified by the user by simply reading the current system time and time zone.
2. Can tell the time of any time zone of any country specified by the user
3. App can convert a specific time from one country to another.
4. When provided with a timezone and course, App can generate the Bootcamp schedule in the time/timezone of any country specified.
5. When provided with a timezone and course,, App Can generate the time left for each bootcmap and alert the user if bootcamp is within 24 hours.


APP MODIFICATIONS:
1. The app is making use of the GUI(ipywidgets) drop down list for making selection and date pickers to pick date.
2.The app is making use of the system's current date and time which is in UTC.
3. They are validations to prevent(input) error in the GUI. 
