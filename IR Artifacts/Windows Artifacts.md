# Windows Artifacts for Incident Response

In an incident response scenario, the following Windows artifacts should be collected to analyze and respond effectively:

## Process and Service Information
- Running Processes
- Running Services
- Parent-Child Process Trees
- Integrity Hash of Background Executables

## Software and User Information
- Installed Applications
- Local and Domain Users
- Unusual Authentications
- Non-Standard Formatted Usernames

## Network Information
- Listening Ports and Associated Services
- Domain Name System (DNS) Resolution Settings and Static Routes
- Established and Recent Network Connections

## Persistence Mechanisms
- Run Key and Other AutoRun Persistence Entries
- Scheduled Tasks

## Execution Artifacts
- Artifacts of Execution (e.g., Prefetch, Shimcache)
- Event Logs

## Security Information
- Anti-virus Detections

These artifacts provide a foundation for identifying malicious activity and understanding the scope of the incident. Additional artifacts may be required depending on the nature of the incident.