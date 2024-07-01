# Basic design of a network topology for a small office setup.

<div style="text-align: center;">

Step 1. Connect to the Internet

  ![Web Browser Image](images/ciscorouter.png)
  <p style="font-size: smaller;"><em>Figure 1: Router -
  The office network connects to the Internet via an ISP-provided connection. This connection is linked to the router</em></p>
  
</div>

<div style="text-align: center;">

     What does it do? 
    
    * Acts as the gateway between the internal network and the external Internet.

    * Translates private IP addresses used within the office network into a single public IP address assigned by the Internet Service Provider (ISP).

</div>

---

<div style="text-align: center;">

Step 2. Router to Firewall

  ![Web Browser Image](images/firewall.png)
  <p style="font-size: smaller;"><em>Figure 2: Firewall - The router (Figure 1) connects to the firewall (Figure 2). The firewall controls access to and from the Internet, providing a layer of security. </em></p>
</div>

<div style="text-align: center;">

     What does it do? 
    
    * Enhances security by controlling and monitoring incoming and outgoing network traffic. It sits between the router and the core switch.

</div>

---

<div style="text-align: center;">

Step 3. Firewall to Core Switch

![Web Browser Image](images/coreswitch.png)
  <p style="font-size: smaller;"><em>Figure 3: Core Switch - The firewall (Figure 2) connects to the core switch (Figure 3). The core switch acts as the main distribution point for the network. </em></p>
</div>

<div style="text-align: center;">

     What does it do? 
    
    * The central hub of the network. Responsible for connecting all different parts of the network together, ensuring efficient data transfer.

</div>

---

<div style="text-align: center;">

Step 4. Core Switch to Access Switches

  ![Web Browser Image](images/accessswitch.png)
  <p style="font-size: smaller;"><em>Figure 4: Access Switch - The core switch (Figure 3) connects to multiple access switches. These access switches handle the distribution of network connections to end devices within the office. </em></p>
</div>

<div style="text-align: center;">

     What does it do? 
    
    * Connects devices within the office, providing scalability. Multiple access switches provide redundancy and improve network performance.
</div>

---

<div style="text-align: center;">

Step 5. Access Switches to Workstations

  ![Web Browser Image](images/workstations.png)
  <p style="font-size: smaller;"><em>Each access switch connects to multiple workstations (PCs, laptops, etc). These connections allow workstations to communicate with each other and access network resources and the Internet. </em></p>
</div>

<div style="text-align: center;">

     What does it do? 
    
    * A computer or device where users perform their daily tasks. It receive network access, allowing users to perform their tasks and access online resources.
</div>

---
<div style="text-align: center;">

Small Office Network Topology in Action

  ![Web Browser Image](images/basicnetworkdiagram.gif)

</div>


</div>
