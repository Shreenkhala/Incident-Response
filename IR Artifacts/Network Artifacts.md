# Network Artifacts for Incident Response

The following network artifacts should be collected and analyzed during an incident response to identify malicious activity and unauthorized access:

## DNS Analysis
- Anomalous DNS traffic and activity
- Unexpected DNS resolution servers
- Unauthorized DNS zone transfers
- Data exfiltration through DNS
- Changes to host files

## Remote Access Evaluation
- Remote Desktop Protocol (RDP), virtual private network (VPN) sessions, SSH terminal connections, and other remote abilities
- Evaluate inbound connections, unapproved third-party tools, cleartext information, and unauthorized lateral movement

## Web and Proxy Analysis
- Uniform Resource Identifier (URI) strings, user agent strings, and proxy enforcement actions for abusive, suspicious, or malicious website access
- Hypertext Transfer Protocol Secure/Secure Sockets Layer (HTTPS/SSL)
- Unauthorized connections to known threat indicators

## Legacy Protocols
- Telnet
- Internet Relay Chat (IRC)
- File Transfer Protocol (FTP)

## Traffic and Routing Analysis
- Look for new connections on previously unused ports
- Look for traffic patterns related to time, frequency, and byte count of the connections
- Preserve proxy logs. Add in the URI parameters to the event log if possible
- Disable LLMNR on the corporate network. If unable to disable, collect LLMNR (UDP port 5355) and NetBIOS-NS (UDP port 137)
- Review changes to routing tables, such as weighting, static entries, gateways, and peer relationships

These artifacts are critical for understanding the nature of network activity and detecting any signs of compromise.