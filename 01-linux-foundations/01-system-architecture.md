

                                 # Lab 01 - Linux System Architecture

## Objective 
Understand how LInux is structured internally and how components interact.

## Topics Covered
- Kernel vs User Space 
- Shell
- System calls
- Processes 
- Hardware interaction
- Filesystem structure

## Command Used
(uname -a, free -h, top, ls, uname -r etc)

## Key Takeaways
- linux uses a well structured filesystem called FHS
- During boot, linuz which is the compressed image of the kernel is loaded together with
initrid which contains the details of the essential drivers, the scripts to run the boot, infact
initrid is essential for boot
- Systemd has a pid of 1 and is responsible for handling all the services the user-space
meaning that if systemd crashes, the system crashes
- The kernel is seperated from the user-space meaning a crash at the user level doesnt affect the kernel.
- Application uses system calls to access drivers or other services
 
