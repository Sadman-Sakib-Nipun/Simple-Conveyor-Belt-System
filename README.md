# Simple-Conveyor-Belt-System

Controlling a simple conveyor belt system by using a modular PLC (Eaton Moeller: XC-CPU201-EC256K-8DI-6DO-XV).

The test environment used for this task is XSOFT-CODESYS-2 V2.3.9 SP7.

The conveyor belt system is driven by a three-phase motor which starts with a delay of 3 seconds after it has been switched on. The conveyor belt is used for transporting packages. Once a certain number of packages have been transported, the system should switch off after a specified rundown time. The number of packages to be transported is 5 and a rundown time of 4 seconds is set.

- The system is switched on via the Start button (NO contact, tap variable).
- The system is switched off immediately via the Stop button (NC contact, tap variable).
- The light barrier (Optogate button) is used to detect the number of packages that have been transported (NO contact, tap variable).
