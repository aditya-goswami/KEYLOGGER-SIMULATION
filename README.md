# KEYLOGGER-SIMULATION
Built Python-based keylogger for lab-based vulnerability demonstration and endpoint security evaluation. Used for SOC Anomaly Use-cases and security awareness training.

 KEYLOGGERS-DETECTION
This project provides an educational tool designed to simulate keylogger attacks and demonstrate a GUI-based detection mechanism. Developed entirely in Python, it serves as a practical, hands-on framework for students and cybersecurity enthusiasts to understand How it works
This repository contains the source code for the paper: "Keylogger Simulation and Detection with GUI: A Lightweight Educational Approach"[cite: 1].

This project provides an educational tool developed in Python to simulate keylogger attacks and demonstrate a GUI-based detection mechanism[cite: 7]. [cite\_start]Its primary goal is to create awareness and provide hands-on learning in a controlled, ethical environment[cite: 10].

 Abstract

Keyloggers are a significant and stealthy cybersecurity threat, capable of capturing sensitive user data[cite: 6]. [cite\_start]This educational tool simulates keylogger behavior using the `pynput` library and provides a real-time detection mechanism using `psutil` for process monitoring[cite: 8]. [cite\_start]The system features a user-friendly graphical interface built with `tkinter` to display alerts and allow for mitigation[cite: 9]. [cite\_start]The results show reliable keystroke capture and successful detection, making it an effective tool for academic and awareness programs[cite: 11].
Project Objectives

  * Create Awareness**: To educate users about the functionality and risks associated with keyloggers[cite: 23].
  * Demonstrate GUI-Based Detection**: To show how a user-friendly interface can simplify threat detection for individuals with limited technical knowledge[cite: 26].
  * Analyze Processes**: To provide a clear understanding of the offensive techniques used by keyloggers and the defensive measures to counter them[cite: 28, 29].

 Methodology

The tool is built with a modular approach:

1.  Keylogger Simulation**: Captures keystrokes using `pynput` and saves them to a local text file[cite: 47].
2.  Detection Module**: Monitors active system processes for suspicious activity using `psutil`[cite: 48].
3.  Graphical User Interface (GUI)**: Built with `tkinter`, it alerts the user and provides options to terminate the malicious process and delete the log file[cite: 49].


Getting Started

Prerequisites

Python 3.x
Required libraries can be installed via pip:

```bash
pip install pynput psutil
```

 Installation & Usage

1.  Clone the repository:

    ```bash
    git clone https://github.com/your-username/keylogger-simulation-gui.git
    cd keylogger-simulation-gui
    ```

2.  **Run the Keylogger Simulation (in a separate terminal):**
    This script will start capturing keystrokes and save them to `keylog.txt`.

    ```bash
    python src/keylogger.py
    ```

3.  **Run the Detection Tool (in another terminal):**
    This will launch the GUI. Click "Scan for Keyloggers" to detect the running simulation.

    ```bash
    python src/main.py
    ```

Ethical Disclaimer

This tool is designed strictly for educational purposes in a controlled environment[cite: 10]. It is intended to help users understand cybersecurity threats, not for any malicious or unauthorized activities. The author is not responsible for any misuse of this software.

 Future Work
Future enhancements could include[cite: 61]:

  * Kernel-level detection for more advanced threats.
  * AI-based behavioral analysis to identify unknown keyloggers.
  * Detection of clipboard and screen logging activities.
  * Cross-platform compatibility for macOS.
