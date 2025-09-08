# ICMP-flood--pcap-inspector
ICMP flood- pcap- inspector,  Python-based tool for analyzing network traffic captured in PCAP files. Its primary focus is detecting ICMP Echo (ping) flood attacks by parsing packet captures and identifying suspicious flood patterns 


Features of the analyzer- 
:PCAP File Upload & Parsing: Upload PCAP files interactively and analyze network packets.
:ICMP Flood Detection: Identifies potential ICMP Echo flood attacks using configurable thresholds.
:Traffic Summary: Generates detailed statistics about total packets, unique IP sources, and top talkers.

Prerequisites
Basic knowledge of Python programming.
Familiarity with networking concepts such as ICMP, TCP/IP, and packet captures.
Google account to access Google Colab (optional but recommended for easy execution).


Installation (If running locally)
Make sure you have Python 3 installed, then run:
"pip install scapy pandas matplotlib seaborn" 


                 Usage
Running in Google Colab

Open the provided Google Colab notebook or upload your .ipynb to Colab.
Run all cells sequentially.
When prompted, upload your PCAP file.
View detailed analysis output and plots directly in the notebook.

Running Locally
Clone the repository.
Install dependencies as above.
Run the main script or notebook.
Upload PCAP file path as input when prompted.

How It Works
Packet Parsing: Uses Scapy to read PCAP files and filter ICMP Echo Requests.
Analysis: Counts packets, identifies flood patterns by detecting traffic spikes, and summarizes source IP activity.
Visualization: Utilizes Pandas and Seaborn to create smooth graphs showing packet rate over time and IP distribution histograms.
Thresholds: Allows dynamic threshold adjustment via interactive controls (if implemented in Colab).
