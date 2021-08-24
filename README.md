IMPORTANT !! It is possible that the project report might be blank when opened on github. If something like this happens, please download the pdf file, and open it on your local machine.

# PRIORITY AND DEADLINE SCHEDULING ALGORITHM

  In a realistic example of CPU Scheduling, it is often the case that some 
processes need to be finished before a fixed amount of time. Also, with these 
deadlines, the processes in themselves carry a weight of importance ( priority ). 

  To give a simple analogy, while making calculations for a game, the calculation check 
ammo strictly must be done before the calculations to fire a bullet, this is analogy 
for the deadline. My Priority & Deadline algorithm is a pre-emptive CPU 
Scheduling Algorithm which takes into account the priority and deadline of a 
process.

  My Algorithm creates a “VIRTUAL TIME CHART” and places the 
processes in such a way that the deadline and the priorities of the processes 
available at that time are respected. Obviously for some rare particular 
arrangement of processes it is impossible to execute all the processes before their 
deadline, but my algorithm will create an optimum time chart to make sure the 
best possible outcome is ensured while respecting the priority and the deadline of 
the process
