# Sysmon-Implementation-Endpoint-Visibility-lab
To build a controlled Windows environment for deep system monitoring, focusing on capturing advanced telemetry that standard Windows Event Logs miss.

That is an excellent choice. It strikes a perfect balance between technical specificity and professional impact.

Here is why that name works well and how you can "flesh out" the project details to make it look impressive on a resume or GitHub profile.

Why this name is a "Winner"
"Sysmon Implementation": Tells the reader exactly what the primary technology is.

"Endpoint Visibility": Highlights the goal (telemetry), which is a high-demand skill in SOC (Security Operations Center) roles.

"Lab": Signals that this was a hands-on, practical build rather than just theoretical study.

Project Overview (The "Elevator Pitch")
If you are listing this project on a resume or LinkedIn, use a structure like this:

Project Name: Sysmon Implementation & Endpoint Visibility Lab Objective: To build a controlled Windows environment for deep system monitoring, focusing on capturing advanced telemetry that standard Windows Event Logs miss.

Key Accomplishments
Deployment: Installed and configured Sysmon64 on a Windows 10/11 sandbox environment using community-standard configurations (e.g., SwiftOnSecurity or Olaf Hartong).

Advanced Telemetry: Configured specific Event ID monitoring for Process Creation (ID 1), Network Connections (ID 3), and DNS Queries (ID 22).

Threat Simulation: Successfully detected "Living off the Land" (LotL) techniques, such as using certutil.exe for file downloads and powershell.exe for encoded command execution.

Analysis: Performed log analysis within the Windows Event Viewer to correlate parent-child process relationships (e.g., Word spawning CMD).
