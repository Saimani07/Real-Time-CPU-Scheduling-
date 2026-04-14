# 🖥️ Real-Time CPU Scheduling Simulator (Java GUI)

A powerful and interactive **Real-Time CPU Scheduling Simulator** built using Java Swing. This application visually demonstrates how different real-time scheduling algorithms work using a **Gantt Chart timeline, logs, and live simulation**.

---

## 🚀 Features

* 📊 Simulates multiple real-time scheduling algorithms:

  * ⏱️ Rate Monotonic Scheduling (RMS)
  * ⏳ Earliest Deadline First (EDF)
  * ⚡ Least Laxity First (LLF)

* 🖼️ Interactive GUI (Java Swing)

* 📈 Visual Gantt Chart Timeline

* 📝 Real-time execution logs

* ⚙️ Dynamic task creation & removal

* 📉 CPU utilization calculation

* ⚠️ Deadline miss detection

* 🔄 Reset and re-run simulation

---

## 🖼️ Application Preview

> Add tasks → Select algorithm → Run simulation → Watch scheduling live!

---

## 🛠️ Tech Stack

* ☕ Java
* 🖥️ Swing (GUI)
* 📊 Data Structures & Algorithms
* 🔄 Multithreading (SwingWorker)

---

## 📂 Project Structure

```text
RealTimeSchedulerSimulator.java
README.md
```

---

## ▶️ How to Run

### 1️⃣ Compile the code

```bash
javac RealTimeSchedulerSimulator.java
```

### 2️⃣ Run the application

```bash
java RealTimeSchedulerSimulator
```

---

## 🧠 How It Works

The simulator models real-time scheduling by:

* Creating task instances periodically
* Maintaining a ready queue
* Selecting tasks based on chosen algorithm:

  * **RMS** → Fixed priority (shorter period = higher priority)
  * **EDF** → Earliest deadline first
  * **LLF** → Minimum slack (laxity) first

It then:

* Executes tasks step-by-step
* Updates Gantt chart visually
* Logs execution events
* Tracks deadline misses and CPU idle time

---

## 📊 Algorithms Overview

### 🔹 Rate Monotonic Scheduling (RMS)

* Fixed priority scheduling
* Tasks with shorter periods get higher priority

### 🔹 Earliest Deadline First (EDF)

* Dynamic priority scheduling
* Task with closest deadline executes first

### 🔹 Least Laxity First (LLF)

* Based on slack time (laxity)
* Executes task with least flexibility

---

## 💡 Future Improvements

* 🎨 Better UI design (modern theme)
* 📊 Advanced charts & analytics
* 💾 Save/load task configurations
* 🌐 Web-based simulation version
* 📉 Performance comparison graphs

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve this project.

---

## 📜 License

This project is open-source under the **MIT License**.

---

## ⭐ Support

If you found this project useful, give it a ⭐ on GitHub!

---

## 👨‍💻 Author

**Sai Manikanta**
GitHub: https://github.com/Saimani07

---
