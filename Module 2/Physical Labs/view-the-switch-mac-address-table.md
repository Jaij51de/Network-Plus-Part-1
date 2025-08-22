# 7.3.7 Lab - View the Switch MAC Address Table

## Topology & Addressing Table

| Device | Interface | IP Address     | Subnet Mask     |
|--------|-----------|----------------|------------------|
| S1     | VLAN 1    | 192.168.1.11   | 255.255.255.0    |
| S2     | VLAN 1    | 192.168.1.12   | 255.255.255.0    |
| PC-A   | NIC       | 192.168.1.1    | 255.255.255.0    |
| PC-B   | NIC       | 192.168.1.2    | 255.255.255.0    |

---

## Objectives

- **Part 1:** Build and Configure the Network  
- **Part 2:** Examine the Switch MAC Address Table

---

## Part 1: Build and Configure the Network

### Step 1: Cable the network according to the topology

**Screenshot Placeholder:**  
`!Network Topology`

---

### Step 2: Configure PC hosts

<img width="975" height="173" alt="image" src="https://github.com/user-attachments/assets/2e9e5a06-4205-45d8-b92a-93a9d48a472c" />

`![PC Configuration](path/to/sStep 3: Initialize and reload switches as necessary

**Screenshot Placeholder:**  
<img width="975" height="369" alt="image" src="https://github.com/user-attachments/assets/7b563a55-a3c7-4155-9d90-ffa5031ac492" />


---

### Step 4: Configure basic settings for each switch

- **Device name**  
- **IP address**  
- **Console and vty passwords: `cisco`**  
- **Privileged EXEC password: `class`**

---

## Part 2: Examine the Switch MAC Address Table

### Step 1: Record network device MAC addresses

1. **PC-A MAC Address:**  
  

2. **PC-B MAC Address:**  
   _Answer:_  

3. **S1 Fast Ethernet 0/1 MAC Address:**  
   _Answer:_  

4. **S2 Fast Ethernet 0/1 MAC Address:**  
   _Answer:_  

---

### Step 2: Display the switch MAC address table

1. **Are there any MAC addresses recorded in the MAC address table?**  
   _Answer:_  

2. **What MAC addresses are recorded in the table? To which switch ports are they mapped and to which devices do they belong?**  
   _Answer:_  

3. **If you had not previously recorded MAC addresses of network devices in Step 1, how could you tell which devices the MAC addresses belong to using only the output from `show mac address-table`? Does it work in all scenarios?**  
   _Answer:_  

---

### Step 3: Clear the S2 MAC address table and display the MAC address table again

1. **Does the MAC address table have any addresses in it for VLAN 1? Are there other MAC addresses listed?**  
   _Answer:_  

2. **Wait 10 seconds and recheck. Are there new addresses in the MAC address table?**  
   _Answer:_  

---

### Step 4: From PC-B, ping the devices on the network and observe the switch MAC address table
1. **How many device IP-to-MAC address pairs have been learned by ARP (excluding multicast/broadcast)?**  
   _Answer:_  

2. **Did all devices have successful replies to pings? If not, check cabling and IP configurations.**  
   _Answer:_  

3. **Has the switch added additional MAC addresses to the MAC address table? If so, which addresses and devices?**  
   _Answer:_  

4. **Does the PC-B ARP cache have additional entries for all network devices that were sent pings?**  
   _Answer:_  

---

## Reflection Question

**What might be some of the challenges on larger networks when switches and PCs dynamically build ARP caches and MAC address tables?**  
_Answer:_  
