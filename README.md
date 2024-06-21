Subject: Threat Advisory: Oyster Backdoor Spreading via Trojanized Software Downloads

Dear Team,

We need to be aware of a new threat involving the Oyster backdoor malware, which is spreading through trojanized installers of popular software. Below are the critical points and recommendations for enhancing our security posture:

Overview:
A malvertising campaign is distributing the Oyster backdoor via fake installers for popular software such as Google Chrome and Microsoft Teams. This campaign redirects users to lookalike websites hosting malicious payloads.

Key Points:
Malware Utilized:

Oyster Backdoor (aka Broomstick, CleanUpLoader): Capable of gathering host information, communicating with a command-and-control (C2) server, and executing remote code.
Infection Vectors:

Trojanized software downloads from lookalike websites.
Fake installers launch malware while installing legitimate software to maintain the ruse.
Attack Techniques:

Users are lured via search engines to malicious sites.
Executable files initiate a malware infection chain.
PowerShell scripts are used for establishing persistence.
Associated Threat Actors:

Linked to ITG23, a Russia-linked group known for TrickBot malware.
Rogue Raticate group using PDF decoys in phishing campaigns to deliver NetSupport RAT.
Recommendations:
Download Vigilance: Only download software from verified and official sources.
Awareness and Training: Educate staff on identifying phishing sites and suspicious downloads.
Endpoint Protection: Ensure robust antivirus and endpoint protection solutions are in place.
Network Monitoring: Implement network monitoring to detect unusual traffic patterns and communications with known C2 servers.
Indicators of Compromise (IOCs):
Unusual download sources and redirects.
Unexpected installation of legitimate software following malware execution.
PowerShell scripts creating persistent mechanisms.
Please remain vigilant and report any suspicious activities to the cybersecurity team immediately.

For detailed analysis and IOCs, refer to the full article here.

Best regards,

[Your Name]
[Your Position]
[Your Contact Information]

# TAMforB
