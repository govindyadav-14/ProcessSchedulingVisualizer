# 🚀 Process Scheduling Visualizer

A responsive, interactive web app to simulate and compare CPU scheduling algorithms. Visualize Gantt charts, turnaround time, waiting time, and discover which algorithm performs best under your custom process load.

## ✨ Features

* **📊 Gantt Chart Visualization** — Displays execution timeline for each process.
* **📋 Process Table** — Shows completion, turnaround, and waiting times.
* **🔄 Algorithm Comparison** — Evaluates all implemented schedulers based on average metrics.
* **🧠 Dynamic Inputs** — Add processes with Arrival Time, Burst Time, and Priority.
* **⏱️ Time Quantum Control** — Customize quantum for RR and preemptive algorithms.

## 🧠 Algorithms Implemented

| Algorithm | Type |
| :--- | :--- |
| **FCFS** | Non-preemptive |
| **SJF** | Non-preemptive |
| **SRJF** | Preemptive |
| **Round Robin (RR)** | Preemptive |
| **Priority (Non-preemptive)** | Non-preemptive |
| **Priority (Preemptive)** | Preemptive |

*Idle times and accurate CPU gaps are visualized using labeled Gantt blocks.*

## 🛠️ Tech Stack

* **⚛️ React with Hooks**
* **🧪 Recoil** for state management
* **🎨 TailwindCSS** for styling
* **🧩 Process Scheduling algorithms** implementations in pure JavaScript

## 🧰 Installation

```bash
# Clone the repo
git clone https://github.com/govindyadav-14/ProcessSchedulingVisualizer.git

# Navigate
cd process-scheduling-visualizer

# Install dependencies
npm install

# Start the dev server
npm run dev

```

## 🔬 Usage

1. **Add Processes:** Use the **Arrival**, **Burst**, and **Priority** fields to input data.
2. **Set Constraints:** Adjust the **Time Quantum** if using Round Robin.
3. **Select Algorithm:** Choose a scheduler from the dropdown menu.
4. **Visualize:** View the generated Gantt chart and calculated metrics.
5. **Compare:** Use the **Comparison View** to see which algorithm performs best for your dataset.

## 🤝 Contributing

Pull requests are welcome! If you'd like to suggest improvements, bug fixes, or new algorithms, feel free to fork the repository and open a PR.

## 📜 License

MIT © Govind
