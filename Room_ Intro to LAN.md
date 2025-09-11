# Room: Intro to LAN
**Platform:** TryHackMe  
**Difficulty:** Beginner  
**Date Completed:** 7th September 2025  

---

## 🗒️Room Summary
This TryHackMe room explained various network topologies. I learnt about the pros and cons of those network topologies which help me to understand which network topology is better depending upon budget and security.

## 🔑Key Takeaways
Topologies are basically network structures.
Different topologies have different advantages over one another.
Star topology is the most popular one because it is easy to setup, offers many ports for devices to connect via a device called switch or hub, it is also fast in speed.
Bus topology is a common and one of the cheapest network topologies. It is useful if number of devices to connect are small in number and communication between them is a basic one.

## Weaknesses of the network topologies 
I used the built-in TryHackMe application to check the weaknesses of the topologies. Bus topology can't handle many requests at a single time, and the newtork crashes if the backbone cable is damaged.
Star topology is one of the expensive as compared to other topologies because it uses a central device or switch, if that switch is damaged, the newtork goes down.
Ring topology or also called a token topology, uses only cables to connect devices in a circle. It has lack of privacy and the network goes down if the cable is damaged.

## Some screenshots here
- Here is the ring topology:
![Ring-Topology](/images/topo1.png)
- Here is the bus topology where I sent multiple requests to crash the network:
![Bus-Topology](/images/topo2.png)
- Here is the star topology:
![Star-Topology](/images/topo3.png)  

## Why topologies matter 
Networking is the backbone of cybersecurity. Different topologies serve different purposes, and that's why they have to be implemented in a different and suitable environment.
