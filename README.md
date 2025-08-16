# 🏥 Hospital Patient Queue

### 📌 Overview

A simple **command-line application** that simulates a hospital's patient queue, designed to prioritize emergency cases over regular ones. Built as an exercise in fundamental **data structures**, it effectively manages patient flow and provides a real-time estimated wait time.

### 🛠 Features

  * **Priority-Based Queuing:** Emergency patients are handled first using a dedicated queue.
  * **Standard Queuing:** Regular patients are managed in a standard first-in, first-out (FIFO) queue.
  * **Estimated Wait Time:** Calculates and displays the estimated waiting time for regular patients.
  * **Menu-Driven Interface:** A user-friendly menu allows for adding patients, serving the next patient, and viewing queue status.

### 📂 Data Structures Used

  * **Deque (`collections.deque`):** Used to efficiently implement the FIFO behavior for both the emergency and regular queues. This allows for fast appends and pops from either end.
  * **Basic Arithmetic:** Employed for a simplified calculation of the estimated wait time.

### 🚀 How to Run

1.  **Save the Code:** Copy the entire Python code into a file named `hospital_queue.py`.
2.  **Run the Program:** Open your terminal or command prompt, navigate to the directory where you saved the file, and run the following command:

<!-- end list -->

```bash
python hospital_queue.py
```
