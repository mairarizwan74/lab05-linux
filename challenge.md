## Question 1

Answer: I am student. My home folder is /home/student.

Commands: whoami, pwd



## Question 2

Answer: The server name is ubuntu and it runs Ubuntu 24.04.3 LTS.

Commands: hostname, head -2 /etc/os-release



## Question 3

Answer: Total RAM and free disk space details.

Commands: free -h, df -h



## Question 4

Answer: Users with /bin/bash access.

Commands: grep /bin/bash /etc/passwd



## Question 5

Answer: Number of running processes.

Commands: ps aux > temp.txt && wc -l temp.txt && rm temp.txt



## Question 6

Answer: Time when lab5user was created and deleted.

Commands: sudo grep lab5user /var/log/auth.log
