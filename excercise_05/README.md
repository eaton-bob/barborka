#excercise 05

### Prolog
Explain MAILBOX (req-rep) pattern on a real world analogy of postman /
postoffice.

What happens when real-world mail box gets full?

### Preparation
Malamute broker is running on given endpoint.
There is a client connected name "`<insert name>`" that responds some very
secret phrase when a "Hello!" string message is sent to it :).

### Task 1
Write a program that
 * connects to given endpoint
 * finds out the secret phrase :)

### Task 2
See what happends when the counterpart is not there (i.e disconnects/connects).

Note: Goal is to show that the broker holds the mailbox messages for disconnected
parties.
