# DNS and ICMP Traffic Analysis Lab

## Objective

This project focused on analyzing DNS and ICMP traffic to investigate a cybersecurity incident where customers experienced website access issues. Using a network protocol analyzer tool (tcpdump), the investigation revealed that UDP packets sent to the DNS server resulted in ICMP error messages indicating "udp port 53 unreachable." The analysis identified the affected network protocol, potential causes such as a Denial of Service (DoS) attack, and highlighted the importance of monitoring IP datagrams for suspicious activity. This project provided hands-on experience in network traffic analysis, incident investigation, and reinforcing network security.

### Skills Learned

- Proficiency in using network protocol analysis tools like tcpdump to investigate network issues.
- In-depth understanding of DNS and ICMP protocols and their roles in network communication.
- Ability to identify and analyze error messages, such as "udp port 53 unreachable," to troubleshoot connectivity issues.
- Enhanced skills in detecting and interpreting potentially malicious traffic on a network.
- Strengthened analytical abilities for assessing security risks and determining the root causes of incidents.
- Practical experience in applying network traffic analysis to reinforce overall network security.

### Tools Used

- Network protocol analyzer tool (tcpdump) for capturing and analyzing network traffic.
- DNS and ICMP traffic logs to investigate connectivity issues.
- IP datagram analysis for identifying suspicious data packets in transit.
- Error message diagnostics to interpret ICMP responses and troubleshoot network problems.
- Documentation tools for recording findings and summarizing incident analysis.


## Steps
![Screen Shot 2024-12-21 at 8 44 24 PM](https://github.com/user-attachments/assets/0cc3ee37-709d-418f-a403-150eda8ccf13)

Ref 1. This screenshot illustrates the investigation of a network issue where users experienced the error "destination port unreachable" when accessing a website. Using tcpdump, it was determined that UDP packets to the DNS server on port 53 were blocked, resulting in ICMP error responses and highlighting a potential DNS server issue.

![Screen Shot 2024-12-21 at 8 46 37 PM](https://github.com/user-attachments/assets/795dc3f5-462a-4ae2-84e8-c93203f4bddf)

Ref 2. This screenshot captures the analysis of a network issue where UDP traffic to DNS port 53 failed, resulting in ICMP error messages. The investigation, conducted at 1:24 p.m. using tcpdump, revealed that the DNS server was unresponsive, likely due to a Denial of Service (DoS) attack or a misconfiguration, preventing proper retrieval of DNS A records.
