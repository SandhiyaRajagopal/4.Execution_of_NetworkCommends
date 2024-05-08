# 4.Execution_of_NetworkCommands
```
NAME: SANDHIYA R
REGISTER NUMBER: 212223240146
```
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

##PROGRAM:
```
from scapy.all import *
target = "www.google.com"
result, _ = traceroute(target, maxttl=32)
print(result)
```
## Output

![image](https://github.com/SandhiyaRajagopal/4.Execution_of_NetworkCommends/assets/144870852/4d889089-aedc-49c6-9e92-7acf1a557b8a)

## Result
Thus Execution of Network commands Performed 
