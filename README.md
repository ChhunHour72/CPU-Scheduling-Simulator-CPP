#CPU Scheduling Simulator in C++
This project simulates four CPU scheduling algorithms:

First-Come, First-Served (FCFS)

Shortest-Job-First (SJF)

Shortest-Remaining-Time (SRT)

Round Robin (RR)

The program provides a menu-driven interface for users to select a scheduling algorithm, input process details, and view the scheduling results, including Gantt charts, waiting times, turnaround times, and average waiting/turnaround times.

Features
Menu-Driven Interface: Users can select a scheduling algorithm from the menu.

Input Validation: Handles invalid inputs (e.g., negative burst times, non-integer inputs).

Output Details:

Gantt Chart: Visual representation of the scheduling order.

Waiting Times: Waiting time for each process.

Turnaround Times: Turnaround time for each process.

Average Waiting Time: Average waiting time for all processes.

Average Turnaround Time: Average turnaround time for all processes.

How to Compile and Run the Program
Prerequisites
A C++ compiler (e.g., g++).

Git (optional, for cloning the repository).

Steps
Clone the Repository (if not already done):

bash
Copy
git clone https://github.com/ChhunHour72/CPU-Scheduling-Simulator-CPP.git
cd CPU-Scheduling-Simulator-CPP
Compile the Program:

Use g++ to compile the C++ file:

bash
Copy
g++ cpu_scheduling.cpp -o cpu_scheduling
Run the Program:

Execute the compiled program:

bash
Copy
./cpu_scheduling
Follow the On-Screen Instructions:

Select a scheduling algorithm from the menu.

Enter the number of processes and their details (Process ID, Arrival Time, Burst Time).

For Round Robin, enter the time quantum.

View the results (Gantt chart, waiting times, turnaround times, and averages).

Example Input and Output
Input
Copy
Number of processes: 4
Processes:
P1: Arrival Time = 0, Burst Time = 6
P2: Arrival Time = 1, Burst Time = 8
P3: Arrival Time = 2, Burst Time = 7
P4: Arrival Time = 3, Burst Time = 3
Output for FCFS
Copy
Gantt Chart: P1 (0-6) → P2 (6-14) → P3 (14-21) → P4 (21-24)
Waiting Times: P1 = 0, P2 = 5, P3 = 12, P4 = 18
Turnaround Times: P1 = 6, P2 = 13, P3 = 19, P4 = 21
Average Waiting Time: 8.75
Average Turnaround Time: 14.75
Repository Structure
Copy
CPU-Scheduling-Simulator-CPP/
├── cpu_scheduling.cpp   # Main C++ program file
├── README.md            # Project documentation
Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure your code follows the existing style and includes appropriate comments.

License
This project is open-source and available under the MIT License.

Contact
For questions or feedback, please contact:

Name: Chhun Hour

GitHub: ChhunHour72
