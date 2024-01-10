
# Edison Academy Magnet School - Student Information System
![image](https://user-images.githubusercontent.com/63886761/223351912-4a8ca7a6-3527-494a-8b71-66fcd7ec8bf8.png)
Edison Academy Magnet School Student Information System (EAMS SIS) is a integrated student management system that allows users to track student progress via integrated quizzes, points tracking, and detailed reporting.

## Features

* <b>NEWS AND EVENTS</b> -- Administrators and post news and events which can be attached to point values that incentivise students to participate in events. Point values can be added simply by using a CSV file uploaded by the administrator.
* <b>USER MODEL</b> -- User model includes the administrator who is capable of the full range of features of EAMS SIS, teachers who manage courses and student grading, and students who receive material and complete assignments. Student points are tracked and monitored, adminstrators can then generate quarterly winners from these points.
* <b>INTEGRATED QUIZZES</b> -- Teachers have the ability to create integrated quizzes within the system that can be created in-house, no third-party platform required. Grades are tracked within the EAMS SIS system and are automatically updated on the gradesheet if teachers choose to record results. Points are also added based on student scores.
* <b>COURSE MATERIAL UPLOAD</b> -- Teachers also have the opportunity to securely upload documents and videos to the website to be stored and viewable to students. Teachers fully manage such uploads.
* <b>DETAILED REPORTING</b> -- Teachers have access to reports regarding students including grades and the respective point values for students.

## Development

* <a href="https://www.djangoproject.com/">Django</a> -- Primary framework for the website which allows for webpage rendering as well as all backend technology. Django comes with a full suite of features that ensures information security while delivering content at fast rates.
* <a href="https://www.mysql.com/">MySQL</a> -- MySQL is utilized in order to store user information as well as other models including courses, quizzes, results for quizzes, point reporting, etc. MySQL is preferable as it integrates easily with Django and is constantly backed up as opposed to SQLite3 files.
* <a href="https://www.digitalocean.com/">DigitalOcean</a> -- DigitalOcean hosts the MySQL database associated with the project and had no costs associated with it due to the benefits provided by the <a>GitHub Student Developer Pack</a>. DigitalOcean provides constant database backup so a new database can be created in an integrity breach.

## Installation

* Clone the repo via the command `git clone https://github.com/Lucky93212/EAMS-SIS/`
* Open a terminal in the cloned folder.
* Ensure you have the relevant dependancies installed including Python, Django, and the necessary Python libraries, if not be sure to install them via the `pip install [LIBRARY]` command.
* Run the command `py manage.py runserver`
* The client should be running on `http://127.0.0.1:8000`

<br>
<div align="center">
© Copyright 2023 <a href="https://github.com/Lucky93212">@Lucky93212</a>. All Rights Reserved.

Unauthorized copying or redistribution of this work is strictly prohibited.

Made in America.
</div>
