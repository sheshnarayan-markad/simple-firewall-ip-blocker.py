# simple-firewall-ip-blocker.py

# 🧱 Simple Firewall IP Blocker

A small Python project that simulates a basic **firewall rule checker**.  
It randomly generates IP addresses and checks them against predefined firewall rules to decide whether to **block** or **allow** each one.


# ⚙️ Requirements
- Python 3.x (no external libraries needed)


# Example output
IP:192.168.1.2, Action:Allow, Random:7452
IP:192.168.1.9, Action:block, Random:293
IP:192.168.1.15, Action:Allow, Random:8201
IP:192.168.1.19, Action:block, Random:4561


#How It Works

The script defines a set of firewall rules (blocked IPs).

It then generates 12 random IP addresses.

For each IP:

If it exists in the rules, action = block

Otherwise, action = Allow
