Network Connectivity Troubleshooting

Date:
Operating System:Windows 11  
Category:Network Support

Objective
Practice diagnosing network connectivity using Windows command-line tools.

 Scenario
A user reports that their computer cannot access websites. The IT Support technician must investigate the network configuration and test connectivity.

Tools Used
- Command Prompt
- `ipconfig /all`
- `ping`
- `nslookup`

 Troubleshooting Steps
1. Inspected the network adapter configuration.
2. Identified the IPv4 address, subnet mask, default gateway, and DNS servers.
3. Tested the local TCP/IP stack using `ping 127.0.0.1`.
4. Tested connectivity to the default gateway.
5. Tested public IP connectivity using `ping 1.1.1.1`.
6. Tested DNS resolution using `nslookup example.com`.

Findings
- The network configuration was inspected using `ipconfig /all`.
- The local TCP/IP stack responded successfully to `ping 127.0.0.1`.
- The default gateway responded to the ping test.
- The public IP address `1.1.1.1` responded to the connectivity test.
- The DNS lookup for `example.com` returned an IP address.

Diagnosis
The diagnostic tests indicated that the computer's local TCP/IP stack was functioning, connectivity to the default gateway was available, public IP connectivity was working, and DNS resolution was successful. No network connectivity issue was identified during these tests.

Resolution
No corrective action was required because the diagnostic tests completed successfully. The results were documented for future reference. If a user still experienced difficulty opening websites, further investigation would be needed into browser settings, proxy configuration, VPN software, or application-specific issues.

 Verification
The connectivity tests were reviewed to confirm that the local TCP/IP stack, default gateway, public IP connectivity, and DNS resolution were responding as expected. The results indicated that basic network connectivity was functioning at the time of testing.

Lesson Learnt
I learned how to investigate network connectivity issues on Windows 11 using Command Prompt. I practiced checking IP configuration with `ipconfig /all`, testing the local TCP/IP stack and network connectivity with `ping`, and checking DNS resolution with `nslookup`. I also learned that troubleshooting should follow a systematic process, starting with local network configuration and moving toward external connectivity and name resolution. This exercise improved my understanding of basic network diagnostics and how to document findings as an IT Support Technician.


<img width="1345" height="932" alt="configuration" src="https://github.com/user-attachments/assets/3a5c58f7-6ceb-4a62-aa7e-840a2659cc02" />

<img width="647" height="350" alt="Screenshot 2026-10-17 125138" src="https://github.com/user-attachments/assets/63e68563-628b-4074-b61c-db4ef2ded7c2" />
<img width="760" height="376" alt="ping test (3)" src="https://github.com/user-attachments/assets/53d622cc-41c2-4d9e-b9b9-ec2cd330d989" />
<img width="356" height="265" alt="nslookup" src="https://github.com/user-attachments/assets/606f95ca-a30d-4c5d-b969-f58c4d3a8814" />
