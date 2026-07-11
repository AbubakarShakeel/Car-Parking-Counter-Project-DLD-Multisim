# Car Parking Lot Counter System (DLD & Multisim)

A digital circuit design for a **Parking Lot Counter System** developed using **Digital Logic Design (DLD)** principles and simulated in **NI Multisim**. This system automates vehicle tracking and capacity management using hardware components without relying on any programming code.

## 🚀 Key Features

*   **Live Tracking:** Dynamically counts and displays the number of vehicles entering and exiting the parking lot.
*   **Visual Display:** Utilizes a 7-segment display to show the current real-time vehicle count.
*   **Capacity Warning:** Automatically triggers an audio buzzer once the maximum capacity of 9 vehicles is reached to block further entry.
*   **Reset Mechanism:** Features a dedicated reset function to clear the counter back to zero for reuse.

## 🛠️ Hardware Components Simulated

The circuit is designed using core DLD components in Multisim:
*   **Up/Down Counter IC:** To increment the count on entry and decrement it on exit.
*   **7-Segment Decoder & Display:** To convert binary data into human-readable digits (0-9).
*   **Logic Gates (AND/OR/NOT):** Used to detect when the counter hits the threshold value of 9.
*   **Buzzer:** Triggered via logic circuits for the maximum capacity alarm.

## 🖥️ How to Run the Simulation

1. Make sure you have **NI Multisim** installed on your PC.
2. Download or clone the `.ms14` (or relevant Multisim version) design file from this repository.
3. Open the file in Multisim and click the **Run/Simulate** button.
4. Use the designated toggle switches to simulate cars entering or exiting, and watch the counter and buzzer respond.
