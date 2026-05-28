# CPU Scheduling Simulator

An interactive web-based simulation tool for visualizing CPU scheduling algorithms including FCFS, SRTF (Preemptive SJF), and Multilevel Feedback Queue (MLFQ).

## 🚀 Live Demo


## 📋 Features

- **Three Scheduling Algorithms:**
  - First Come First Served (FCFS) - Non-preemptive
  - Shortest Remaining Time First (SRTF) - Preemptive SJF
  - Multilevel Feedback Queue (MLFQ) - Configurable queues & aging

- **Interactive Process Management:**
  - Add/remove processes dynamically
  - Edit arrival and burst times
  - Visual PID color coding

- **Step-by-Step Learning Mode:**
  - Play/Pause execution
  - Previous/Next step navigation
  - Live explanation of each scheduling decision

- **Detailed Visualizations:**
  - Dynamic Gantt chart with exact timestamps
  - MLFQ queue visualization (live)
  - Performance metrics (Avg WT, Avg TAT, CPU Utilization, Throughput)

## 🖥️ Tech Stack

- HTML5 Canvas for Gantt chart rendering
- CSS3 with modern Flexbox/Grid layout
- Vanilla JavaScript (no dependencies)
- Responsive design for all screen sizes

## 📊 Sample Output

| Algorithm | Avg Waiting Time | Avg Turnaround | CPU Util |
|-----------|-----------------|----------------|----------|
| FCFS      | 3.33            | 6.67           | 100%     |
| SRTF      | 2.33            | 5.67           | 100%     |
| MLFQ      | 2.33            | 5.67           | 100%     |

## 🎯 How to Use

1. Edit process arrival/burst times in the table
2. Select scheduling algorithm (FCFS/SRTF/MLFQ)
3. For MLFQ: Configure queues, quanta, and aging threshold
4. Click **Run Simulation** to see complete Gantt chart
5. Click **Enable Step-by-Step Mode** to walk through each decision


