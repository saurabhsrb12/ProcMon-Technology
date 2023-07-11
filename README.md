ProcMon - Process Monitoring Tool:
=
ProcMon is a process monitoring tool developed in C++ that allows you to monitor and manage processes running on a Windows system. It provides information about processes, threads, and dependent DLLs, and offers functionalities such as process display, logging, searching, and termination.

Features:
=
Display detailed information about processes, including process name, PID, parent PID, and thread count.
View information about threads associated with a process.
Explore the dependent DLLs of a process.
Log the information of running processes to a file.
Read and display information from log files.
Search for specific running processes.
Terminate processes.

Getting Started:
=
To get started with ProcMon, follow these steps:

Clone the repository to your local machine.
Open the project in an IDE or text editor that supports C++ development.
Build the project to generate the executable file.
Run the executable from the command line to start ProcMon.

Usage:
=
ProcMon provides a command-line interface for interacting with the tool. Here are some available commands:

**ps** : Display information about all running processes.  

**ps -t** : Display information about threads for each process.  

**ps -d** : Display information about dependent DLLs for each process.  

**log** : Create a log file with information about running processes.  

**readlog** : Read and display information from a specified log file.  

**search [process_name]** : Search for a specific running process.  

**kill [process_name]** : Terminate a specified process.  

**sysinfo** : Display hardware configuration information.  

**clear** : Clear the console screen.  

**help** : Display help information about available commands.  

**exit** : Terminate ProcMon.  


Dependencies:
=
This project relies on the following libraries:

Windows API: The project uses the Windows API functions for process and system information retrieval.
Contributions
Contributions to ProcMon are welcome! If you find any bugs, have suggestions for improvements, or want to add new features, please feel free to submit a pull request.

License:
=
This project is licensed under the MIT License. You are free to use, modify, and distribute this software. Refer to the LICENSE file for more information.

Contact:
=
For any questions or inquiries, please contact [Your Name] at [Your Email].

Enjoy using ProcMon and monitoring your processes efficiently!
