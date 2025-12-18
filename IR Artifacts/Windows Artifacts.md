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