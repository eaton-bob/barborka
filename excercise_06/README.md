# excercise 06

### Preparation
Malamute broker is running on given endpoint.

There is a client "`<insert name>`" that:
 * upon receiving START string message using MAILBOX, starts sending each 0-3
   seconds INTEGER string message on stream "`<insert name>`" and replies with
   OK
 * upon receiving STOP string message using MAILBOX, stops publishing on stream
   "`<insert name>`" and responds with OK
 * for any other MAILBOX message responds with ERROR/COMMAND-UNKNOWN


### Task 1
Write a program that
 * connects to given endpoint
 * subscribes to stream
 * sends START
 * prints artihemtic mean from stream for some time (...tbd...)
 * sends STOP  

Note: Also try to send something bogus to the client 
