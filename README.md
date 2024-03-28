# SIEM-Lab

## Objective


Employ a Security Information and Event Management (SIEM) system to enhance threat detection, incident response, and overall cybersecurity posture by aggregating, correlating, and analyzing security data from diverse sources to proactively identify and mitigate security threats and breaches.


### Skills Learned
- Advanced grasp of SIEM concepts and their practical implementation.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and identify attack signatures and patterns.
- Enhanced understanding of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Splunk
## Steps


![IMG_8604](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/52137f12-a762-4f00-93ec-49d0551fee32)

Utilizing Splunk, I can analyze data and search through individual datasets to pinpoint specific information. Currently, I'm examining data concerning an unidentified attacker's IP address, "40.80.148.42," targeting a website named "iamnotbatman.com" with the IP address "192.168.250.70." Splunk presents all events linked to the attacker's IP, offering comprehensive details including source IP, destination IP, ports, and timestamps. Through the search bar and interface fields, I can tailor my search to identify indicators of compromise (IOCs).

![IMG_8605](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/69f212e5-93b9-4260-ac0d-b2af55747d44)

Modifying field values allows for more nuanced searches. For example, specifying the field value "alert.category" filters events classified as potential attacks.

![IMG_8606](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/9ac614f5-b579-4688-994c-b789047b5a5b)

![IMG_8607](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/0aaef9c8-b344-49f9-bf48-c4645944f68f)


Choosing "Attempted Administrator Privilege Gain" unveils additional details regarding the attacker's methods and techniques employed in the attempted privilege escalation. Splunk also pinpoints the CVE (Common Vulnerabilities and Exposures) linked to the attack.


![IMG_8608](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/a60a0b08-bb79-4a63-8664-76b012ae15dd)

Looking up the identified CVE offers a comprehensive description of the attacker's intentions and the vulnerability exploited to gain administrative privileges. This insight is essential for mitigating potential exploits in the future.

Source:(https://nvd.nist.gov/vuln/detail/cve-2014-6271)

![IMG_8609](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/b28405e6-f138-4805-9b3f-2dc1b7e9c656)

Returning to Splunk and examining the fields, clicking on "URL" allows identification of numerous potentially exploitable CGI values.


Using Splunk as a SIEM offers organizations a powerful platform for comprehensive security information and event management. It enables real-time monitoring, analysis, and correlation of security events across the entire IT environment. With Splunk, users can detect and respond to threats quickly, thanks to its advanced analytics, machine learning capabilities, and customizable dashboards. It facilitates compliance management, incident investigation, and threat hunting, empowering security teams to strengthen their defenses and safeguard their organization's data and assets effectively.
