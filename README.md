When you set up Moodle in your machine, upload from Moodle setting the 'backup-moodle2-course-2-πληροφορική-20240114-1958.mbz' file 

-fix MySQL xampp 
  set port 3307
  
  C:\xampp\mysql:
  Rename folder mysql/data to mysql/data_old
  Make a copy of mysql/backup folder and name it as mysql/data
  Copy all your database folders from mysql/data_old into mysql/data (except mysql, performance_schema, and phpmyadmin folders)
  Copy mysql/data_old/ibdata1 file into mysql/data folder
  Start MySQL from XAMPP control panels.
