# senate-bus-problem

## Problem Statement
This problem was originally based on the Senate bus at Wellesley College. Riders come to a bus stop and wait for a bus. When the bus arrives, all the waiting riders invoke boardBus, but anyone who arrives while the bus is boarding has to wait for the next bus. The capacity of the bus is 50 people; if there are more than 50 people waiting, some will have to wait for the next bus. When all the waiting riders have boarded, the bus can invoke depart. If the bus arrives when there are no riders, it should depart immediately.

## Solution
The solution is based with semaphors in java to wait and signal threads through concurrent execution of multiple threads.

### Compile program
>javac SemaphoresTest.java
### Run program
>java SemaphoresTest.java