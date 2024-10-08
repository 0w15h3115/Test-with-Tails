# Test with Tails | Beta


**Test with Tails is a script to install well-loved pentesting tools on Tails OS (Nmap, Ncat, Impacket, Sliver, Netexec, Burp Suite)**

**Deals with the quirks of installing these tools through ONLY tor, including permissions issues**

**Must be run in root terminal**


Remember to create an admin password when logging into tails

Download the raw file if git clone gives errors or use wget, and make it executable (chmod +x) before running in a root shell.

Opening an Apache server on your distribution of tails will poke a hole in your persec

Will need to use burpsuite gui installer downloaded by the script after running


**All network traffic must go through tor. ICMP and UDP traffic are not available over tor. For example, to perform a network scan with nmap it must be run with the no ping (-Pn) flag, as well as run through proxychains/Torify**


<img src="https://kids.kiddle.co/images/1/1a/Miles_%22Tails%22_Prower_Sonic_and_All-Stars_Racing_Transformed.png" width="200" height="200" />

## Liability Disclaimer

Disclaimer of Liability and Responsibility

This script (hereinafter referred to as “the Script”) is provided for educational purposes and for legal penetration testing or system security enhancement only. By using the Script, you agree to the following terms:

1. Authorized Use Only: 
You acknowledge and agree that the Script is to be used solely on systems and networks that you either own or have explicit permission to access. Unauthorized use of this Script on third-party systems, networks, or devices is strictly prohibited and is considered illegal under applicable laws, including but not limited to computer fraud and abuse laws.
	

2.	No Responsibility for Misuse:
The author(s) of this Script shall not be held liable for any illegal, unethical, or unauthorized use of the Script. Any use of this Script to conduct activities that violate any local, state, national, or international laws or regulations is strictly prohibited. You assume full responsibility for any damage, legal action, or harm caused as a result of the misuse of the Script.
	

3.	Acknowledgment of Legal Penalties:
You understand that using the Script in a manner that violates the law may subject you to criminal charges, civil litigation, or penalties. You agree to comply with all applicable laws, regulations, and guidelines regarding cybersecurity, data protection, and privacy.
	

4.	Disclaimer of Warranties:
The Script is provided “as is” without any warranties, express or implied. The author(s) make no warranties or representations regarding the functionality, performance, or results obtained through the use of the Script. No guarantee is provided that the Script is free of defects or that it will function properly in all scenarios.


5.	Indemnification:
You agree to indemnify and hold harmless the author(s) of the Script from any claims, damages, liabilities, losses, or expenses, including legal fees, arising out of your use or misuse of the Script, your violation of any third-party rights, or your breach of any terms in this disclaimer.


6.	Governing Law:
This disclaimer and any disputes related to the Script or its usage shall be governed by and construed in accordance with the laws of the jurisdiction in which the author(s) of the Script reside, without regard to conflicts of law principles.


7.	Termination of License:
The author(s) reserve the right to revoke permission to use the Script at any time and for any reason. Continued use of the Script after such a notice is strictly prohibited.
