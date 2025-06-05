# Analyzing Network Attacks Using Packet Sniffer Wireshark

Consider a scenario where a customer of a company experiences a security issue when accessing the company’s website. The goal is to identify the likely cause of the service interruption. Then, explain how the attack occurred and the negative impact it had on the website. Understanding how attacks impact a network will help troubleshoot issues on an organization’s network. It will also help to take steps to mitigate damage and protect a network from future attacks.

## What was provided

- **[Wireshark TCP/HTTP log](http://docs.google.com/spreadsheets/d/1enpRzrIao3J2Lp2tOI0hmu1Cu7D7CjLGhFAiTiR9J64/edit?gid=218501934#gid=218501934)**
  
## Activity


### Scenario

In this activity, I work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, I receive an automated alert from my monitoring system indicating a problem with the web server. I attempt to visit the company’s website, but I receive a connection timeout error message in my browser.

I use a packet sniffer to capture data packets in transit to and from the web server. I notice a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. I suspect the server is under attack by a malicious actor. 

### Incident Response

I take the server offline temporarily so that the machine can recover and return to a normal operating status. I also configure the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. Because I know that my IP blocking solution won’t last long as the attacker can easily spoof other IP addresses to get around this block, I need to alert my manager about this problem quickly and discuss the next steps to stop this attacker, and also prevent this problem from happening again. I therefore prepare to tell my boss in an Incident Report, about the type of attack I discovered and how it was affecting the web server and employees.
