# Room: Packets and Frames  
**Platform:** TryHackMe  
**Difficulty:** Beginner  
**Date Completed:** 13th September 2025  

---

## 🗒️Room Summary  
This TryHackMe room explained how data is broken down and sent across networks using packets and frames. I learnt how information travels from one device to another and how different layers of networking handle this data. It helped me understand the flow of communication at a more detailed level.  

## 🔑Key Takeaways  
- Data is divided into **packets** so it can be sent efficiently over the network.  
- Packets contain source and destination IP addresses to make sure they reach the correct device.  
- Each packet is wrapped in a **frame** at the Data Link layer for delivery within the local network.  
- Frames include MAC addresses, error-checking information, and other metadata.  
- When packets arrive at the destination, frames are stripped and packets are reassembled into the original data.  

## 🖥️Practical Learning  
- I used the TryHackMe virtual machine to observe packet transmission.  
- I checked how IP addresses and MAC addresses are included in packets and frames.  
- Practiced visualizing how a message from my device is broken into packets, sent across a network, and reassembled at the other end.  

## Some screenshots here  
- Here I understood the three-way handshake that occurs during a tcp connection between two devices with the help of THM side-quest:  
![Packet-Example](/images/tcp2.png)  
- I also used netcat to try to connect to an IP Address with a port too:  
![Frame-Example](/images/tcp3.png)  

## Why packets and frames matter  
Understanding packets and frames is essential for networking and cybersecurity. It shows how data actually moves through a network, and it’s the first step to analyzing traffic, spotting errors, or detecting malicious activity.
