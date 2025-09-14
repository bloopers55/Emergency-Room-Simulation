# Emergency-Room-Simulation
Project Overview

# Domain
- This Simulation will be simulating real world emergency waiting rooms, which have queues that need to respond to affliction urgency and unexpected variables like new symptoms presenting while in the queue that may change the queue order.
  
# Problem Statement
- This Simulation will answer the following questions
1. What is the optimal allocation of staff resources in a dynamic environment, where there will be rushes of patients and lull periods.
2. How can we improve the efficiency of patient throughput, while still addressing rush cases with the proper urgency.
3. Does inefficiency in check in increase patient mortality.
4. How many staff per patients should we aim for in emergency rooms.
   
# Scope
Patients will enter with a Poisson distribution rate, so there will be lulls and rushes.
The ER will have an adjustable number of staff that can dynamically change their assignment from helping with intake/diagnosis to treating patients. The staff number can only be changed at the beginning of the simulation
Patients will be full of data such as name, birthday, insured, and other factors
The simulation will be given 100 patients to process.
Patients will enter the ER, check in with a nurse, their info will be processed, and then they will be inserted into the queue.
The nurse will take time to check them in, and their info will take time to be processed as well.
The patient info will include an urgency, which will factor into their placement in queue, but this is only known after their info is taken.
The patient info will include complexity which will represent how long it will take to treat them.
Some patients will have a death time tied to urgency, if these patients aren’t treated quickly enough they will die in the waiting room.
In total there will be a queue that will represent a line to put your info in, and a separate line representing people sitting in the waiting room.
The simulation will run on ticks representing 1 minute each roughly.
