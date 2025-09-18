# OSFall2025_hw0 // EECE.4811
Operating Systems Fall 2025 Class. Homework #0

---------------------------------------

## How to Run both problems:
Make sure you have Go installed (version 1.25.x or newer// does matter linux/macos or windows enviroment). 
And chek the dependencies/library for each programm.

Open a terminal inside the `hw0/` folder and run:
go run hw0.go/  

-----------------------------

##Designs:
*For the 1st problem:
The program has two parts: Producer and Consumer.
The Producer makes numbers 1 to 5 and sends them to the Consumer.
The Consumer prints the numbers and then sends back an "ack" to the Producer.
I used pipes so they can talk to each other, and the Producer waits for the ack before sending the next number.
This keeps happening until both reach 5 times the cycle.

---------------------
## Used dependencies/library
For problem #1 the 2 libraies used where os and os/exce to be able to use more smple wy to use the concept learn in class about about the tack output from one procces comes to the second one and backfoward 

For problema #2 

