# Blue Team Laboratory Setup Snort - ELK Stack
This is a step by step guide on how to setup Snort (IDS) in conjunction with Elasticsearch, Kibana and Logstash (SIEM).
This also includes some guide on how to simulate the attack on a laboratory environment using Kali Linux VM Machine.

## The Setup

- Internet 
    - Local Network
        - Windows Local Machine 
            - VM1 (Snort and FileBeat) 
            - VM2 (ELK Stack) 
            - VM3 (Kali Linux)
            - Other Target VM (optional)


## The VM Operating System
- Windows (Local Machine)
- Ubuntu Servers (SNORT and ELK Stack)
- Kali Linux (Attack Machine)
- Vulnerable Machines (Target Machine, optional)

## VM Network Configuration
- Use Bridged Network or Host only

