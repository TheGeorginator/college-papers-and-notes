



### Overview

**What You Will Learn:** Touchstone Tasks help you apply course concepts to real network artifacts. In this Unit 2 Touchstone Task you will analyze GreenLeaf’s switching environment, including switch roles, MAC address behavior, VLAN assignments, and trunking. You will examine packet flows, identify switching functions, and document how VLANs segment the network. You will work with the following GreenLeaf artifacts:

- [Layer 2 Switch Topology Diagram](https://app.sophia.org/download/attachment/63627-Switch_Topology_Diagram.txt) [STP_Topology_Output.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%202/STP_Topology_Output.txt.md)
- [The VLAN Assignment Table](https://app.sophia.org/download/attachment/63628-VLAN_Assignment_Table.txt) [VLAN_Assignment_Table.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%202/VLAN_Assignment_Table.txt.md)
- [Spanning Tree Protocol Output (All Switches)](https://app.sophia.org/download/attachment/63630-STP_Topology_Output.txt) [STP_Topology_Output.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%202/STP_Topology_Output.txt.md)
- [Portland Core Switch Configuration](https://app.sophia.org/download/attachment/63631-Portland_Core_Switch_Config.txt) [Portland_Core_Switch_Config.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%202/Portland_Core_Switch_Config.txt.md)
- [Portland Access Switch Configuration](https://app.sophia.org/download/attachment/63632-Portland_Access_SW1_Config.txt) [Portland_Access_SW1_Config.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%202/Portland_Access_SW1_Config.txt.md)
- [Eugene Core Switch Configuration](https://app.sophia.org/download/attachment/63633-Eugene_Core_Switch_Config.txt) [Eugene_Core_Switch_Config.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%202/Eugene_Core_Switch_Config.txt.md)
- [Cable Infrastructure and Physical Layer Documentation](https://app.sophia.org/download/attachment/63634-Cable_Infrastructure_Plan.txt) [Cable_Infrastructure_Plan.txt](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%202/Cable_Infrastructure_Plan.txt.md)

**Why It Matters:** Switching is the foundation of all wired networks. Understanding how switches forward frames, learn MAC addresses, and carry VLANs is essential for troubleshooting and for designing scalable networks. This Touchstone builds on your Unit 1 work by focusing on how Layer 2 devices shape traffic inside each site. **What You Will Hand In:** Submit a single PDF, two to three pages, that includes:

- A diagram labeling switching roles (core vs access) and VLAN trunk paths
- One table summarizing VLANs and where they appear
- Short explanations of MAC learning, forwarding, and broadcast behavior
- A brief description of how a packet moves through the switched network

**Keys to Success:**

- Describe switching behavior using correct Layer 2 terminology
- Use artifacts from the GreenLeaf Resource Pack as evidence
- Keep explanations concise and accurate
- Include at least one labeled diagram and one table
- Develop and submit original work

**Helpful Links:**

- Academic Integrity Guidelines (for all Touchstones)
- Ethical Standards and Appropriate Use of AI (for all Touchstones)

[Share your feedback on Touchstones](https://app.sophia.org/spcc/introduction-to-networking-2-touchstone-task-2-1#)

### Instructions

**Step 1: Review the GreenLeaf Switching Artifacts**  
Use the [Unit 2 Documentation Worksheet](https://app.sophia.org/download/attachment/63635-ITN%20Unit%202%20Touchstone%20Task%20Student%20Template.docx) [ITN Unit 2 Touchstone Task Student Template.docx](/Sophia%20Resources/02.01%20-%20Introduction%20to%20Networking/Touchstone%202/ITN%20Unit%202%20Touchstone%20Task%20Student%20Template.docx.md) and GreenLeaf Resources.  
  
Review:

- VLANs, port assignments, and site usage in the VLAN Assignment Table
- Core and access switch roles in the Layer 2 Switch Topology Diagram
- Spanning tree root selection and port roles in the Spanning Tree Protocol Output
- Trunking, access port settings, and port security in the
- Portland Core Switch Configuration
- Portland Access Switch Configuration
- Trunking and VLAN distribution in the Eugene Core Switch Configuration
- Physical cabling types, distances, and backbone links in the Cable Infrastructure and Physical Layer Documentation

**Step 2: Analyze Switching Roles and VLAN Placement**  
Create or annotate a diagram showing:

- The core and access switches at both Portland and Eugene
- Trunk links between switches and which VLANs they carry
- Where each VLAN appears in the network based on the VLAN Assignment Table

Label your diagram with VLAN IDs when possible.

**Step 3: Explain Switching Behavior**  
Using the switch configurations and STP output, write short explanations of:

- How switches learn MAC addresses on access and trunk ports
- How they forward unicast, broadcast, and unknown-unicast frames
- How VLANs create separate broadcast domains across the network

You may reference ARP behavior conceptually, but rely on the VLAN table, topology diagram, and switch configs for evidence.

**Step 4: Summarize VLAN Assignments and Trunking**  
Create a table listing each VLAN in GreenLeaf’s network and indicate:

- VLAN name and purpose
- Which site(s) use the VLAN
- Which trunk uplinks must carry the VLAN based on the switch topology diagram and configuration files

Include specific interfaces (for example: Gi1/0/2 on PDX-CORE-SW01).

**Step 5: Describe Key Layer 2 Operations**  
Choose one example of Layer 2 behavior (for example: a workstation sending traffic to its gateway, or a wireless client associating to an AP). Briefly describe:

- How the frame moves through access and core switches
- Where VLAN tagging occurs on trunk ports
- How STP ensures there are no loops on the path

Keep the focus on Layer 2 concepts rather than inter-VLAN routing.

**Step 6: Review and Submit**  
Export your completed worksheet to a single PDF and include your name and date.

### Self Assessment

![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) I identified switch roles accurately.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) My VLAN table matches the GreenLeaf documentation.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) Port assignments come from real configuration files.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) STP behavior matches the “show spanning-tree” output.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) Port security details are tied to specific interfaces.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) My explanations are original, concise, and accurate.  
![square](https://cdn2.sophia.org/wiris_cache/082fcb2ba9de5a08e33188dd8484e68e.png) I created a clean, well-organized PDF.