# Question 1: Current user and home folder
Answer: I am logged in as tuba-zainab. My home folder is /home/tuba-zainab.
Commands: whoami, pwd 

# Question 2: Server name and Ubuntu version
Answer: My server name is ubuntu. I am using Ubuntu 24.04.1 LTS.
Commands: hostname, cat /etc/os-release | head -2

# Question 3: RAM and free disk space
Answer: My server has approximately 1.6 GiB of RAM. My root filesystem has 11 GB available disk space.
Commands: free -h, df -h

# Question 4: Users that can log in with /bin/bash
Answer: The users shown with /bin/bash shell are root and tuba-zainab.
Command: grep "/bin/bash" /etc/passwd

# Question 5: Number of processes
Amswer: The command reported 230 lines, including the header. Therefore, there are approximately 228 process entries.
Command: ps aux | wc -l

# Question 6: Creation and deletion time of lab5user
Answer: The creation time was 2026-10-16 04:35:52 UTC. The deletion time was 2026-10-16 04:42:56 UTC.
Command: sudo grep lab5user /var/log/auth.log
