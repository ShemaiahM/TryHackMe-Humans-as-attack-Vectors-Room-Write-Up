# TryHackMe-Humans-as-attack-Vectors-Room-Write-Up

# TryHackMe Humans as Attack Vectors
## Employees at Risk/Human Vectors
 
### SOC Analyst: Continuous Co-worker Protection
 
**Objective:**
Identify Attack Vectors & Mitigation
 
**Tools Used**
* TryHackMe
* Browser
* TryHackMe VM/ security dashboard

### Skills Demonstrated
* **Phishing Triage:** Identifying and analyzing malicious emails.
* **Incident Response:** Blocking threats and initiating impact analysis.
* **Log Analysis:** Interpreting security alerts within a dashboard.
* **Security Awareness:** Understanding human-centric attack vectors.
 
**Actions:**

Phishing email attempt by sender stating that there has been
a payment and what makes this suspicious is it is directed to Mark Philips
Finance Director. What makes this special is the person its directed to, the
Finance Director. 
The stripe-payments.xyz, different domain
name than that of support@stripe.com, I can tell this is domain spoofing.
The correct action is to block and start an analysis on where, who, what and how this email got through. 
The example below is just one of four dealt with.
 
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/f70d670e-a17d-4c3f-bc1b-f9a63788b3a9" />

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/b0f4136b-5206-46a2-b84b-513df748daca" /> 

Deepfake Phone Spoofing 
Phone Spoofing & Deepfake a Co-worker of the team had a an odd phobecall from the CEO at (pm asking to reste the password tohis Gmail account. Two things that stood out, the co-worker getting a phonecall at 9pm after working hours, not while in the office wokring hours.  The next big clue, the hidden phone number. Phone Spoofing and Deepfake calls always are called from resticted or hiden numbers, so the call cannot be traced back.

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/6bd63d04-e1e8-42e8-be8b-59077d7c9a36" />

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/86653d6e-2bab-4b55-8292-63f461a06a26" />


**What I Learned**
* Who is at risk, employees/co-workers in different departments.
* Common phishing tactics i.e. Phishing emails with payment invoices with different domain names.
* Deepfakes and Phone Spoofing.
* What A SIEM Dashboard may look like.
* Daily duties of a SOC Analyst and encounters.
* Identification and Mitigation of Malicious methods and tactic, i.e. insecure downloads.

**Conclusion**
TryHackMe simulation of day-to-day SOC Analyst. I will face
multiple indicators of compromise and attack vectors used by Threat actors. In this
regard, how Threat Actors use Social Engineering / human psychology to manipulate
& get to intended targets and what methods they will use to do so i.e. phishing
emails and domain name spoofing and unsecure download zip files etc. 




