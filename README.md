<snippet>
  <content><![CDATA[

# ${1:Process Scheduler}

## Requirements
1. Bash terminal
2. Gcc compiler

## Installation
1. Pull from repo
2. cd into directory
3. in command terminal enter "Make"
## Description
C program to demonstrate how process scheduling works

Program Objectives:
A)Define Processes

B)Add one to the ready queue, run the loop at least once then add the next.

C)loop until all processes exit. Each iteration is one time unit.Adjust time counters in each process

D) swap processes as necessary from CPU to either the I/O or ready queue

E)swap processes from I/O to ready queues when I/O time is up

F)Adjust priority of processes in ready queue so no processes waits too long and so higher priorities run first.

G) After the loop stops and all process have exited print the statistics for the OS setup for time limits

each process’s stats including total, min and max times

All I/O times should be > 2

]]></content>
  <tabTrigger>readme</tabTrigger>
</snippet>
