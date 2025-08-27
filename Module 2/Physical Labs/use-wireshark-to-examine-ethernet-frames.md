# 7.1.6 Lab - Use Wireshark to Examine Ethernet Frames

## Objectives

- **Part 1:** Examine the Header Fields in an Ethernet II Frame  
- **Part 2:** Use Wireshark to Capture and Analyze Ethernet Frames

---

## Part 1: Examine the Header Fields in an Ethernet II Frame

### Step 1: Review the Ethernet II header field descriptions and lengths

| Field               | Length         |
|--------------------|----------------|
| Preamble            | 8 Bytes        |
| Destination Address | 6 Bytes        |
| Source Address      | 6 Bytes        |
| Frame Type          | 2 Bytes        |
| Data                | 46–1500 Bytes  |
| FCS                 | 4 Bytes        |

---

### Step 2: Examine the network configuration of the PC

**Screenshot Placeholder:**  
<img width="975" height="715" alt="image" src="https://github.com/user-attachments/assets/e272c418-dd01-48f9-bc8b-95a5594c32b6" />

---

### Step 3: Examine Ethernet frames in a Wireshark capture

**Screenshot Placeholder:**  
<img width="975" height="697" alt="image" src="https://github.com/user-attachments/assets/59b387e0-9509-449d-82cf-9b8d1ce9d260" />


---

### Step 4: Examine the Ethernet II header contents of an ARP request

1. **What is significant about the contents of the destination address field?**  
   There are two types, 12 digits and the one in the last is the same address of the pc being used in the screenshot 
2. **Why does the PC send out a broadcast ARP prior to sending the first ping request?**  
  The PC only knows the IP address, ARP (address resolution protocol) is a protocol used for determining the MAC address associated with an IP address and the frame needs that MAC address before it can travel.

3. **What is the MAC address of the source in the first frame?**  
   Dell_50:fd:c8 

4. **What is the Vendor ID (OUI) of the Source NIC in the ARP reply?**  
Netgear (30:46:91:99:c5:72)

5. **What portion of the MAC address is the OUI?**  
   _The source address

6. **What is the NIC serial number of the source?**  
   F0-1F-AF-50-FD-C8

---

##
