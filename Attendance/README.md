# Attendance-App
<h3>Introduction</h3>
This project helps Teachers to take attendance and store, fetch data from mysql db using server (php).

# Features
- Beautiful LoginScreen.
- Teachers will be able to take attendance and save in database on server.
- Fetch attendance data according to calendar date selection.

# How it works
- First Teachers/Mentor/Other Login from LoginScreen (currently user login is predefined in mysql)
- Select Subject Name.
- Select Time,Batch,Status(present/absent).
- Select rollno.
- When submit button selected, all selected rollno is saved on mysql database (backend php server).
- Check record of attendance data from attendanceView section,Which display student present/absent from selected date.

# GuideLines

 <b> Setup:-</b>
 <br> </br>
	1. Create demo2 database in mysql (from localhost/phpmyadmin).
	<br> </br>
	2. Select demo2 and import database file (from database folder/demo2.sql).
	<br> </br>
	3. Browse to c/wamp/www/create/ or c/xammp/htdocs/  create attendance folder and paste all php files inside attendance folder (from php/attendance).
	<br> </br>
	
  <b> Localhost Testing:- </b>
  <br> </br>
	1. Start Wamp/Xampp server.
	<br> </br>
	2. In cmd run "ipconfig" command (make sure your pc/laptop is connected to network via lan/wifi) and note the ip of lan/wifi network .
	<br> </br>
	3. Open project in android studio.
	<br> </br>
	4. Change url address as per your ip address(from step 2) in com/java/attendance/misc/utils/Constants.java file
		<br> </br>
		<b>These url :-</b>
	<br> </br>
	 		 public static final String LOGINURL = "http://192.168.0.102/attendance/login.php"
			 <br> </br>
			 public static final String INSERTATTEND = "http://192.168.0.102/attendance/insertAttendance.php"
			<br> </br>
		         public static final String VIEWATTENDANCE = "http://192.168.0.102/attendance/viewAttendance.php"
			<br> </br>
			 public static final String QUICKATTENDANCE = "http://192.168.0.102/attendance/quickAttendance.php"	
	<br> </br>
	5. Build app in android studio.
	<br> </br>
	6. Finally test app in emulator/phone (for phone, you should config wamp to work on your phone ).<br>

# Note
1. User login details is predefined (manually insert login details in demo2/teacher table).

# ScreenShots


# Library

<p>
 <ul>
 <li>
       <a href="https://github.com/amitshekhariitbhu/Fast-Android-Networking"><b>Fast-Android-Networking</b></a>
 </li>
     <li>
        <a href="https://github.com/vikramkakkar/SublimePicker"><b>SublimePicker</b></a>    
    </li>
 </ul>
 </p>

# Contact :

 <p>mailto:m.mohsin.iqbal@gmail.com</p>

