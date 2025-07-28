# TCPDump-Network-Traffic-Analysis
This project focuses on using TCPDump to capture and analyze network traffic across different layers of the OSI model. TCPDump is a powerful command-line tool that allows us to monitor and inspect network packets in real-time.

Introduction

TCPDump is a widely-used network sniffing tool that enables users to capture and analyze data traffic from any layer of the OSI model. In this project, we explore basic and advanced usage of TCPDump, including applying filters to narrow down traffic, capturing specific types of data, and exporting results for further analysis.

# Skills Required
Network Traffic Analysis: Gained hands-on experience in capturing and analyzing network traffic using TCPDump.

Filtering Techniques: Learned to apply various filters to narrow down traffic based on host, destination, protocol, and port.

Subnet Scanning: Explored how to capture traffic across an entire subnet.

Data Exporting: Practiced exporting captured data into .pcap files for further analysis in tools like Wireshark.

Command-Line Proficiency: Improved command-line skills by working with TCPDump and its options.

# documentation
Basic Usage

To start capturing network traffic, you can use the following command:
```
tcpdump -i eth0
```
![image alt](https://github.com/KRakeshkumar0011/TCPDump-Network-Traffic-Analysis/blob/main/images/1.png?raw=true)

* -i: Specifies the interface to capture traffic from (e.g., eth0 for Ethernet or wlan0 for Wi-Fi).
This command captures all traffic on the specified interface, which can result in a large amount of data. To make the output more manageable, we can apply filters.

Applying Filters
Filter by Host

To capture traffic from a specific host, use:





