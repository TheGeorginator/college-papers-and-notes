[02.01 - Introduction To Networking](/Courses/02.01%20-%20Introduction%20To%20Networking.md)

**Known variables:**
- **Network Address / Network ID** = 10.20.10.0
- **CIDR Notation** = /25

**Step 1:** Calculate **Subnet Mask:**
- **CIDR Notation** = /25
- Add each **octet**: 11111111(255).11111111(255).11111111(255).1000000(128) (25 bits)
**Subnet Mask** = 255.255.255.128
>[!Notes on this]
>This should be doable in reverse, i.e. calculating the CIDR Notation from the Subnet Mask. 
>Likely by breaking down the final number into binary, and counting that.
>Also, the /24 CIDR notation opens up the full bit to 255, for more addresses.

Step 2: Calculate **Broadcast Address:**
- **Broadcast Address** is always 1 less than **next network address**. (\[Final Subnet Mask Octet (128)\] - 1 = 127 | Place at **Final Network Address Octet**
- **Broadcast Address** = 10.20.10.127

**Step 3:** Determine **First + Last Usable IPs**, and **Number of Usable Hosts**:

- **First Usable IP: Network Address** + 1 = 10.20.10.1
- **Last Usable IP: Broadcast Address** - 1 = 10.20.10.126
- **Number of Usable Hosts**:
	- CIDR Bits: 25 (From CIDR Notation, /25)
	- Available Bits: 32
	- Host Bits: 32(A.B.) - 25(C.B.) = 7
	- **Usable Hosts Formula:**
		- 2ˣ (**X** = **Host Bits**) (128) - 2 = **126**

Step 4: Report Findings!
- Usable Hosts: 126
- First Usable IP: 10.20.10.1
- Last Usable IP: 10.20.10.126
- Broadcast Address: 10.20.10.127