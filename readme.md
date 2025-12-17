This is a C-based Intrusion Detection System (IDS) that uses libpcap for real-time network traffic analysis.
It implements port scan detection logic by tracking unique destination ports per source IP within a configurable time window.
Alerts are streamed to an embedded Mongoose web dashboard, enabling operators to visualize threats and block malicious IPs via iptables.
