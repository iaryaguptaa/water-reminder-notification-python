# Desktop Water Reminder Application (Python)

A lightweight background automation utility built in Python that monitors time intervals and pushes native desktop notifications to remind users to stay hydrated.

This project demonstrates background process looping, thread delaying using core modules, and integration with cross-platform native notification APIs.


## Features & Technical Highlights

* Native OS Notifications: Leverages the plyer library to bridge python scripts directly into system-level notification engines across platforms.
* Infinite Time Looping: Implements an intentional infinite while True loop structure to keep the script executing continuously as a background daemon process.
* Thread Delay Precision: Uses time.sleep() tracking algorithms to scale execution waiting blocks accurately (e.g., delay handling for 3600 seconds to execute hourly alerts).
* Dynamic Display Tuning: Configured native notification features including specific window titles, clean body text strings, and timeout auto-dismiss latency handling.


## How To Run Locally

1. Clone the Project:
git clone https://github.com/iaryaguptaa/water-reminder-notification-python.git

2. Install Dependencies:
pip install plyer

3. Navigate and Run:
cd water-reminder-notification-python
python main.py

4. Setup: Leave the terminal window running in the background, and it will automatically ping you with pop-up notifications to drink water every hour!


## Key Learnings
* Orchestrating lightweight automation daemons using endless control structures safely.
* Interfacing external hardware alert wheels through Python wrappers.
* Implementing timing configurations for recurrent background task management.
