## **Cerf & Kahn: TCP/IP (1974)**

### **What problem existed?**

By the early 1970s, there were several different computer networks (like ARPANET and PRNET), but they were like people speaking different languages. They couldn't talk to each other. If you were on one network, you couldn't send a message to someone on another. There was no "inter-net"—just a series of "intranets." We had the hardware, but we didn't have a universal handshake.

### **What did this person actually do?**

Vint Cerf and Bob Kahn published a paper titled *"A Protocol for Packet Network Intercommunication."* They designed the **Transmission Control Protocol (TCP)** and the **Internet Protocol (IP)**. Instead of the network being responsible for the "reliability" of a message, they put that responsibility on the individual computers at the ends of the connection. This allowed the network itself to stay simple, flexible, and capable of connecting any two machines on Earth.

### **Why did it unlock something?**

It created a **"Network of Networks."** TCP/IP provided a standardized way to break data into "packets," address them, and send them across any physical medium—wires, radio waves, or satellite. It was designed to be "agnostic" to the hardware. This meant the network could grow infinitely large without anyone having to "re-invent" the internet every time a new type of computer was built.

### **What wouldn't exist without it?**

* **The Global Internet:** Every bit of data that moves from a server to your screen today is wrapped in TCP/IP "envelopes."
* **Cloud Computing:** The ability for an AI to sit in a data center in Oregon and answer a prompt from someone in Tokyo relies entirely on this protocol.
* **The Common Crawl:** The massive datasets (like the one GPT was trained on) only exist because TCP/IP allowed us to scrape the entire world's interconnected information into one place.
