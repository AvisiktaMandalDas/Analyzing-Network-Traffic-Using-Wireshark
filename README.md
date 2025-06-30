# Analyzing-Network-Traffic-Using-Wireshark

# Objective
Capture live network packets and analyze common protocols used during regular browsing activity.

# Tools Used
- Wireshark (v4.x)
- macOS Terminal

# Steps Followed
1. Installed Wireshark via Homebrew on macOS M1.
2. Captured traffic on Wi-Fi interface (`en0`) for 1 minute.
3. Generated traffic by browsing websites and pinging servers.
4. Stopped capture and applied protocol filters (http, dns, icmp).
5. Exported capture to `.pcap` format.
6. Analyzed protocols involved in the session.

# Protocols Identified
1. DNS: Domain Name Resolution- Queries to resolve google.com
2. HTTP: Web traffic-	Visiting wikipedia.org
3. ICMP: Ping packets-	From ping google.com
