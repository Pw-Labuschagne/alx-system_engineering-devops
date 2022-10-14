Processes and signals

General

    What is a PID
    What is a process
    How to find a process’ PID
    How to kill a process
    What is a signal
    What are the 2 signals that cannot be ignored

Copyright - Plagiarism

    You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
    You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
    You are not allowed to publish any content of this project.
    Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements
General

    Allowed editors: vi, vim, emacs
    All your files will be interpreted on Ubuntu 20.04 LTS
    All your files should end with a new line
    A README.md file, at the root of the folder of the project, is mandatory
    All your Bash script files must be executable
    Your Bash script must pass Shellcheck (version 0.7.0 via apt-get) without any error
    The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
    The second line of all your Bash scripts should be a comment explaining what is the script doing

The tasks are:

#0.Write a Bash script that displays its own PID.
#1.Write a Bash script that displays a list of currently running processes.
#2.Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.
#3.Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.
#4.Write a Bash script that displays To infinity and beyond indefinitely. 
#5.We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this.

Write a Bash script that stops 4-to_infinity_and_beyond process.
#6.Write a Bash script that stops 4-to_infinity_and_beyond process.

Requirements:

    You cannot use kill or killall

#7.Write a Bash script that displays:

    To infinity and beyond indefinitely
    With a sleep 2 in between each iteration
    I am invincible!!! when receiving a SIGTERM signal

Make a copy of your 6-stop_me_if_you_can script, name it 67-stop_me_if_you_can, that kills the 7-highlander process instead of the 4-to_infinity_and_beyond one.

#8.Write a Bash script that kills the process 7-highlander.
