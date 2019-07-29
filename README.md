# AutoProcessLogger-Python 3.0
...

This automation scripts takes snapshot of processes such as its name, PID, memory usage, thread count and number of child processes. scripts executes periodically by the time specified by the user of script.
After taking snapshot of processes it creates a log file and sends it to specified email address.

Important modules used:-
   psutil : iter_process() function is used to take snapshot of process
   smtplib & email : To send attached log file to user
   time : time.ctime is used to get currunt time for making log file
   schedule : To schedule tasks in script

Usage:-
$Script_name Dir_Name Time(Min) Reciever_Mail_Id

Tip:-
Turn on "Less secure apps on" senders gmail account.
