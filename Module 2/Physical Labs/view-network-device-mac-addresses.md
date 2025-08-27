# 7.2.7 Lab - View Network Device MAC Addresses

## Topology & Addressing Table

| Device | Interface | IP Address     | Subnet Mask     | Default Gateway |
|--------|-----------|----------------|------------------|------------------|
| S1     | VLAN 1    | 192.168.1.2    | 255.255.255.0    | N/A              |
| PC-A   | NIC       | 192.168.1.3    | 255.255.255.0    | 192.168.1.1      |

---

## Objectives

- **Part 1:** Configure Devices and Verify Connectivity  
- **Part 2:** Display, Describe, and Analyze Ethernet MAC Addresses

---

## Part 1: Configure Devices and Verify Connectivity

### Step 1: Cable the network as shown in the topology

**Screenshot Placeholder:**  
<img width="830" height="747" alt="image" src="https://github.com/user-attachments/assets/285b0b7b-8fb3-4099-b404-f6de457ea24e" />


---

### Step 2: Configure the IPv4 address for the PC

- **Were the pings successful? Explain.**  


---

### Step 3: Configure basic settings for the switch

**Screenshot Placeholder:**  
`<img width="975" height="448" alt="image" src="https://github.com/user-attachments/assets/4c5e5e56-01b6-4a3e-b255-3c856583dd70" />

- **Were the pings successful?**  
  _Answer:_  

---

## Part 2: Display, Describe, and Analyze Ethernet MAC Addresses

### Step 5: Analyze the MAC address for the PC-A NIC

1. **What is the OUI portion of the MAC address for this device?**  
5C-26-0A

2. **What is the serial number portion of the MAC address for this device?**  
   24-2A-60  

3. **Using the example above, find the name of the vendor that manufactured this NIC.**  
 00-15-5D-

4. **Identify the OUI portion of the MAC address for the NIC of PC-A.**  
00-15-5D-

5. **Identify the serial number portion of the MAC address for the NIC of PC-A.**  
  1A-99-F2

6. **Identify the name of the vendor that manufactured the NIC of PC-A.**  
   Microsoft

---

### Step 6: Analyze the MAC address for the S1 VLAN 1 interface

1. **What is the MAC address for VLAN 1 on S1?**  
  172.26.0.1

2. **What is the MAC serial number for VLAN 1?**  
   7D-02-09  

3. **What does BIA stand for?**  
   Burned in address

4. **Why does the output show the same MAC address twice?**  
  Multiple connection types from the same device  

---

### Step 7: View the MAC addresses on the switch

1. **What Layer 2 addresses are displayed on S1?**  
  ff-ff-ff-ff-ff-ff
01-00-5e-00-00-02
01-00-5e-00-00-c8


2. **What Layer 3 addresses are displayed on S1?**  
   172.19.255.255
224.0.0.2



---

## Reflection Questions

1. **Can you have broadcasts at the Layer 2 level? If so, what would the MAC address be?**  
  Yes FF:FF:FF:FF:FF:FF

2. **Why would you need to know the MAC address of a device?**  
  To ensure data packets are being sent to the right place/ device
