# BUILDING A NETWORK: Packet Tracer - Logical and Physical Mode Exploration

## Objective

This exercise uses Cisco Packet Tracer to explore both the Logical and Physical Modes of network topology. In Logical Mode, the focus is on a high-level view of the network layout, disregarding physical aspects, while Physical Mode considers the actual scale and placement of devices. Additionally, understanding the differences in device placement is also crucial: heavy devices like servers and network equipment are mounted on racks, personal devices like PCs and laptops are placed on tables, and shelves are used for storing unused devices.

### Skills Learned

- Investigating devices in a wiring closet.
- Connecting end devices to networking devices via different cables.
- Installing networking devices on to the rack.
- Configuring of network devices such as routers.

### Tools Used

- Cisco Packet Tracer

## Steps

### 1. Investigate Devices in a Wiring Closet
1. Navigate to the Branch Office wiring closet in Seward.
    
    ![1 1 6 Packet Tracer Tutored Activity - Logical and Physical Mode Exploration - 1 - Map Overview - 1](https://github.com/user-attachments/assets/6d608483-daa3-49b9-82b4-dd245dac579c) <br>
    *Ref 1: Map Overview*.
    
2. Connect a PC to a switch (ALS2) using an ethernet cable.

   <img src="https://github.com/user-attachments/assets/ecd9b875-c329-44b9-ba68-658028456b94" 
   alt="PC1 to ALS2 via Ethernet Cable"
   width="325" height="280"> <br>
   *Ref 2: PC1 to ALS2 via Ethernet Cable*.

### 2. Connect End Devices to Network Devices
PCs and laptops can be connected to networking devices using a console cable or USB cable to provide management access.
Management access is used to view and change device configurations.
1. Connect RS232 port on the PC to the console port on the Edge Router via console cable.

    <img src="https://github.com/user-attachments/assets/a65dcd6f-7857-47a5-9004-dac02cef125d"
    alt="Edge Router to PC 1 via Console Cable"
    width="325" height="280"> <br>
    *Ref 3: Edge Router to PC1 via Console Cable*.

### 3. Install a Backup Router
Newer models of networking devices can be connected to laptops and PCs via USB ports.
1. Install a new router in the Rack and power it on.
2. Connect the laptop to the new router with a USB cable.

    <img src="https://github.com/user-attachments/assets/8e7587b3-35e9-49aa-aeb1-d329a88dd641"
    alt="Install Backup Router and Connect to Laptop 1 via USB Cable"
    width="325" height="280"> <br>
    *Ref 4: Install Backup Router and Connect to Laptop1 via USB Cable*.

### 4. Configure a Hostname 
Every computer, including network devices, such as routers and switches, requires an operating system to function.
The operating system allows the device hardware to function and provides an interface for users to interact.
The Cisco Internetwork Operating System (IOS) is an operating system used in Cisco networking devices.
It allows creation of configurations that customize the operation of network devices in different network environments.
The CLI is accessible via the device console port using terminal software or remotely via Secure Shell (SSH).
Network devices are assigned a host name for identification and configuration.
1. In the laptop, access the Desktop tab and click Terminal. Click OK to initiate the terminal connection.

    <img src="https://github.com/user-attachments/assets/7948b5c3-66ce-4547-ac2a-d7835c61a2da"
    alt="Accessing the Terminal on the Laptop"
    width="460" height="200"> <br>
    *Ref 5: Accessing the Terminal on the Laptop*.

2. Answer no to the initial question and press ENTER to reach the Router> command prompt.

    <img src="https://github.com/user-attachments/assets/2f21c56c-73f3-44d2-a09b-8ae67d600a7e"
    alt="Changing the Hostname - Part 1"
    width="435" height="90"> <br>
    *Ref 6: Changing the Hostname 1*.
  
3. Enter the following commands (in **bold**) to name the router: 

    <img src="https://github.com/user-attachments/assets/6b94320a-79d8-437d-982f-3c259022143b"
    alt="Changing the Hostname - Part 2"
    width="770" height="88"> <br>
    *Ref 7: Changing the Hostname 2*.

    <img src="https://github.com/user-attachments/assets/ef7c44ad-91d0-49ae-bb79-d4f61a75df4c"
    alt="Changing the Hostname Results"
    width="730" height="220"> <br>
    *Ref 8: Changing the Hostname 3*.

## Resources

  A brief introduction for the Cisco Packet Tracer can be found here:<br>
  https://www.youtube.com/watch?v=M66J7oRU400&t=94s
