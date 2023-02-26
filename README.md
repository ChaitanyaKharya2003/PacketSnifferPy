# PacketSnifferPy
 Python2.7 Script for Packet Sniffer

 Run in Linux Command Line as:
1. In line 45 of arpspoof.py, edit the target_ip variable to the IP you want to Spoof.
2. On the Terminal: run -> 
python arpspoof.py
OR
python3 arpspoof.py
3. Check the interface that you want to use using ifconfig(on linux based OS) and ipconfig(on Windows OS).
4. According to the interfaces display, edit line 33 in packetSniffer.py, and change the interface argument (set as eth0 by default) accordingly.

In arpspoof.py:
    For Python 3 compatibility:
    1. Comment out lines 66, 67.
    2. Uncomment line 70

    Python Libraries used:
    1. re
    2. scapy
    3. subprocess
    4. time
    5. sys


