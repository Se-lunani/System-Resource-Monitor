System Resource Monitor
This Python script monitors the system's CPU, memory, and disk usage. If any of these resources exceed a predefined threshold (10% in this case), 
the script sends an alert email to the specified recipient. If the email cannot be sent, the script prints the alert message to the console.

Features
Monitors CPU, memory, and disk usage.
Sends an email alert if usage exceeds 80%.
Prints the alert message to the console if the email fails to send.
Runs the monitoring check every 5 minutes.
Requirements
Python 3.x
psutil library
