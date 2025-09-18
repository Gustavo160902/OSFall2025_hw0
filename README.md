# OSFall2025_hw0 // EECE.4811
Operating Systems Fall 2025 Class – Homework #0

-----------------

## How to Run Both Problems
Make sure you have Go installed (version 1.25.x or newer).  
It does not matter if you are using Linux, macOS, or Windows or WSL.  

Check the dependencies/libraries for each program.  

Open a terminal inside the hw0 folder and run:
go run hw0.go OR click in run at the top left of vsc(assuming you are using it)

BOTH PROGRAM WERE ONLY TEST IN VSC (WINDOWS AND WSL)
##Designs

Problem #1:
The program has two process Producer and Consumer.
The Producer makes numbers 1 to 5 and sends them to the Consumer.
The Consumer prints the numbers and then sends back an "ack" to the Producer.
I used pipes so they can talk to each other.
The Producer waits for the ack before sending the next number.
This repeats until both reach 5 cycles.

--------------------

Problem #2:

----------------------

##Dependencies / Libraries Used
Problem #1
The 2 libraries used were os and os/exec.
They made it easier to use the concepts learned in class about how the output from one process can be sent to the second one and then back.

----------------------

Problem #2:


