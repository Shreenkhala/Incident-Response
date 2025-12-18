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

---

## Additional Windows Artifacts for Incident Response

### Shortcut (LNK) Files
- LNK files store information about shortcuts created by users or programs. These can provide evidence about the execution of programs, their locations, and access timelines. 

### Recycle Bin
- Forensic data from the Recycle Bin can reveal deleted files' original locations, deletion timestamps, and the user who deleted the file. It can provide context for malicious data removal attempts.

### Browser Artifacts
- Browser history, cookies, and cache can shed light on web activity, including communication with external entities, data exfiltration, or phishing attempts. Relevant browsers include Chrome, Firefox, Edge, etc.

### Registry
- The Windows Registry contains configuration settings and activity traces. Investigate keys related to persistence, application usage, or indicators of compromise, such as `Run` keys, `MountedDevices`, and `UserAssist`.

### Jump Lists
- Jump Lists provide details about the most recently and frequently accessed files and programs. These are relevant for identifying user activity and uncovering potential malicious execution.

These artifacts diversify incident response capabilities and are critical in understanding adversary techniques.

Ensure to collect these artifacts alongside previously identified categories during an incident investigation.