 VPN Traffic Analysis Project

 What I Did
I used ProtonVPN and Wireshark to capture and analyze network traffic. I compared what happens when you use a VPN versus when you don't.

 Why This Matters
VPNs protect your privacy by hiding your internet activity. This project shows how they work and proves they actually protect you.

 Tools I Used
- Wireshark (to capture network traffic)
- ProtonVPN (to create a secure connection)
- Internet browser (to generate normal web traffic)

 My Test Process
1. Without VPN: Captured my normal internet traffic
2. With VPN: Captured traffic through ProtonVPN
3. Compared both to see the differences

 What I Found

 Without VPN:
- My real IP address was visible
- Websites I visited were visible in the traffic
- DNS requests (like website lookups) went to my ISP

With ProtonVPN:
- Only the VPN server's IP was visible (my IP was hidden)
- All traffic was encrypted (couldn't see what websites I visited)
- DNS requests went through ProtonVPN's servers

Key Discoveries
- VPNs really do encrypt all your traffic
- No DNS leaks were found (all queries stayed in the VPN tunnel)
- The kill switch worked (blocked internet if VPN disconnected)
- Some apps bypass the VPN if not configured properly

 What I Learned
1. How to use Wireshark to capture real network traffic
2. How to verify if a VPN is actually protecting you
3. The importance of checking for DNS leaks
4. Why VPNs are essential on public Wi-Fi

Full Documentation
I wrote detailed notes about this project here:

https://drive.google.com/drive/folders/1QtalTwUHZSBP7zsxRKRP9F_S91BUO0c7?usp=sharing

(This link goes to my documentation where I explain everything with screenshots)

 Skills This Project Shows
- Network traffic analysis
- Privacy protection verification
- VPN technology understanding
- Security tool usage (Wireshark)
