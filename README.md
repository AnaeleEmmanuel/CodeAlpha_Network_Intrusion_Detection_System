

 
# Network Intrusion Detection System

This project involves the development of a Network-Based Intrusion Detection System (NIDS) it is designed to monitor and analyze network traffic for suspicious activities. The system is configured to detect potential threats using Suricata, with custom rules and alerts for enhanced threat detection.

## Project Outlines
* Monitor Network Traffic: Search and analyze real-time network data to identify malicious activities.
* Custom Rules: Create and implement detection rules tailored to specific threats and suspicious networks
* Alert System: Configure notifications for detected intrusions.
* Visualization: Display's detected attacks using visualization tools and settings for better insight.

## Features
* Real-Time Monitoring: Continiously scans network data for malicious behaviours.
* Customizable Rules: Define the rules to detect specific types of threats.
* Alerts: Trigger alerts for potential intrusions to ensure quick responses and solutions.
* Attack visualization: Used the linux command-line to visualize threats.

## Setup requirements
### prerequsites
* Linux-based system (recommended)
* Suricata installed.

1. ### Installation 
Follow the Installation guide here `https://suricata.io/`

2. ### Clone the Repository
git clone https://github.com/anaeleemmanuel/CodeAlpha_Intrusion_Detection.git  
cd CodeAlpha_Intrusion_Detection  

3. ### Set up Rules
* Define the custom rules in the `rules/` directory
* Add them to suricata configuration.

4. ### Run the IDS: 
* Suricata e.g:
`sudo suricata -T -c /etc/suricata/suricata.yaml -v`

5. ### Enable Alerts:
Alerts will be logged and saved to the `logs/` directory






## Usage
* Modify Rules: Adjust the rules in `rules/` to match your specific rules requirements.
* Monitor Logs: Always check the `logs/` directory for alerts.
* Respond to Threats: Take action based on detected threats and malicious actions(e.g block ip's and notifying admins and higher authorities.)

### Disclaimer 
This project is intended for educational and security purposes only. It should not be used for malicious activities or unauthorized monitoring. Always comply with suricata laws and organizational policies for a better and effective digital experiences.

### Acknowledgements
* Tools: Suricata and Linux based.
* Developeda as part of the CodeAlpha internship program.

