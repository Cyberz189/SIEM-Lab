# SIEM-Lab

## Objective
[Brief Objective]

Employ a Security Information and Event Management (SIEM) system to enhance threat detection, incident response, and overall cybersecurity posture by aggregating, correlating, and analyzing security data from diverse sources to proactively identify and mitigate security threats and breaches.


### Skills Learned
- Advanced grasp of SIEM concepts and their practical implementation.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and identify attack signatures and patterns.
- Enhanced understanding of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
[Bullet Points]

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Splunk
## Steps


![IMG_8604](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/52137f12-a762-4f00-93ec-49d0551fee32)

Using Splunk i'm able to breakdown data and search individual datasets to track down information i am looking for. In this case i am looking for data that relates to an unknown attacker IP address "40.80.148.42" which is being used to attack a website called "iamnotbatman.com" who has the IP address of "192.168.250.70". Splunk is able to show all the events associated with the attacker IP and gives all the details of the source ip, destination ip, ports, and the time of the event. The search bar on top of the screen and fields on the left side of the screen, allow me to manage how i would like to identify IOCs.

![IMG_8605](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/69f212e5-93b9-4260-ac0d-b2af55747d44)

Adjusting the fields value allows me to get more in depth with my searches. In this case, i used fields value " alert.category" to show all the events that registered an event and was categorized as a potential attack.

![IMG_8606](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/9ac614f5-b579-4688-994c-b789047b5a5b)

![IMG_8607](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/0aaef9c8-b344-49f9-bf48-c4645944f68f)


By selecting "Attempted Administrator Privilege Gain" i was able to get more details of the attacker and the methods and techniques used to try and get administrative privileges. Splunk was also able to identify the CVE (Common Vulnerabilities and Exposures) used in the attack.

![IMG_8608](https://github.com/Cyberz189/SIEM-Lab/assets/163569052/a60a0b08-bb79-4a63-8664-76b012ae15dd)

By searching up the identified CVE i'm able to get a detailed description of what the attacker had in mind, as well, as the vulnerability used to get adminstravtive privilages. Knowing this information is crucial in trying to mitigate any potential exploit going forward.




Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*
