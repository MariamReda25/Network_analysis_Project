Network Task Requirements Document
1. Objective

The primary objective of this network task is to analyze network traffic using Wireshark and automate specific tasks with a Bash script, generating a summary report.
2. Scope

    Capture network traffic using Wireshark.
    Develop a Bash script to analyze the captured data.
    Extract relevant information like total packets, protocols, and top source/destination IP addresses.
    Generate a summary report based on the analysis.

3. Prerequisites

    Wireshark installed.
    Permission to capture network traffic.
    Basic Bash scripting knowledge.

4. Wireshark Capture

    Start Wireshark and capture network traffic.
    Save the captured data in a pcap file (e.g., your_capture_file.pcap).

5. Bash Script

    Create a Bash script named analyze_traffic.sh.

    Use the script to: a. Specify the path to the Wireshark pcap file. b. Analyze the data to identify patterns. c. Extract information like total packets, protocols, etc. d. Generate a summary report.

Hints:

    Research Wireshark command-line tools like tshark for packet analysis.
    Use filters to focus on HTTP (http) and HTTPS/TLS (tls) protocols.
    Explore options for counting packets, extracting IP addresses, and generating summary statistics.

6. Output
The Bash script should output a summary report containing identified patterns and key statistics.
