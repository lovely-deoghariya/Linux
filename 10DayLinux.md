(1) create a directory named linux_week1 inside it create files app.py, notes.txt and data.csv
Ans: mkdir linux_week1
     cd linux_week1
     touch app.py notes.txt data.csv
(2) Create a backuo directory, copynotes.txt into it then rename the copied file to notes_backup.txt
Ans: mkdir backup
     cp notes.txt backup/
     mv backup/notes.txt backup/notes_backup.txt
(3) Move data.csv into the backup directory and verify its contents using is
Ans: mv data.csv backup/
     ls backup
(4) Delete app.py then create and remove an empty directory named temp
Ans: rm app.py
     mkdir temp
     rmdir temp
(5) Display your command history and then print your current working directory 
Ans: history
     pwd
