# FUTURE_CS_02 - Phishing Email Detection & Awareness Report

**Author:** IGNAS EDD MALEWA  
**CIN ID:** FIT/APR26/CS8072  
**Date:** May 2026  
**Task:** Phishing Email Detection & Awareness - Future Interns Task 2

---

## What is This Task?

Phishing is one of the most common cyber attacks. Attackers send fake emails pretending to be real companies like Netflix, banks, or delivery services. Their goal is to trick people into clicking malicious links or sharing passwords.

In this task, I acted as a security analyst. I analyzed real phishing email samples, identified the red flags in each one, and created an awareness report that businesses can use to train their employees.

---

## What I Did

I analyzed three different phishing email samples:

**Email 1 - Netflix Scam**
This email claimed the user's payment had failed and asked them to update their billing information. The sender was billing@netflix-account.com (fake) and the link went to a suspicious .xyz domain.

**Email 2 - Delivery Service Scam**
This email claimed a package could not be delivered and asked the user to track their shipment. The sender was tracking@issued-delivery.net (fake) and the link used a deceptive .xyz domain.

**Email 3 - Bank Scam**
This email claimed unusual activity was detected on the user's account and asked them to verify their identity. The sender was alerts@trust-security.com (fake) and the link led to a fake login page on a .xyz domain.

---

## Key Findings

After carefully analyzing all three emails, I found the following red flags:

Fake Sender Domains
All three emails came from fake domains. For example, the Netflix email came from @netflix-account.com instead of the real @netflix.com. Attackers register fake domains that look similar to real ones to trick users.

Suspicious Links
All three emails contained links to .xyz domains. Legitimate companies like Netflix, FedEx, and Chase use .com domains, not .xyz. The .xyz domain is cheap and commonly used by attackers.

Generic Greetings
None of the emails used the recipient's real name. They all used generic greetings like "Dear Customer" or "Dear Valued Customer." Real companies usually know your name and use it.

Urgency and Fear Tactics
All three emails tried to create a sense of urgency. The Netflix email said payment failed. The delivery email said package could not be delivered. The bank email said account may be blocked. Attackers use fear to make people act quickly without thinking.

Grammar Errors
Two of the three emails had grammar or spelling errors. The bank email said "You're account may be burned" which should be "Your account may be blocked." Real companies do not make these mistakes.

---

## Classification Result

All three emails were classified as PHISHING with HIGH RISK. This means they are definitely malicious and intended to steal personal information or money.

---

## What I Created

I created a detailed awareness report that includes:
- Simple explanation of what phishing is and why it is dangerous
- Analysis of each email with screenshots
- List of red flags to look for
- Prevention guidelines for employees (do's and don'ts)
- What to do if you suspect a phishing email

The report is written in simple, non-technical language so any employee can understand it.

---

## Repository Structure

This repository contains all my work for Task 2:

FUTURE_CS_02/
├── README.md (this file - explains the whole project)
├── evidence/
│   ├── html_samples/ (HTML versions of the 3 emails)
│   │   ├── netflix.html
│   │   ├── delivery.html
│   │   └── bank.html
│   ├── netflix.txt (raw email text)
│   ├── delivery.txt
│   └── bank.txt
└── report/
    ├── Phishing_Awareness_Report.pdf (main report - the key deliverable)
    ├── netflix_email.png (screenshot of Netflix email)
    ├── delivery_email.png (screenshot of delivery email)
    └── bank_email.png (screenshot of bank email)

---

## Prevention Tips for Employees

Always check the sender's email address before reading any message. Look carefully at what comes after the @ symbol. If it does not match the real company domain, it is phishing.

Always hover your mouse over any link before clicking. Look at the bottom left of your browser to see the real destination. If the link does not match the company name, do not click.

Never enter your password after clicking a link in an email. Real companies will never ask you to do this.

Be suspicious of any email that creates urgency, uses generic greetings, or asks for personal information.

If you suspect an email is phishing, do not click anything. Forward it to your IT department and delete it immediately.

---

## Conclusion

This task demonstrated how to identify phishing emails using simple but effective techniques. All three analyzed samples were clearly phishing based on fake sender domains, suspicious links, generic greetings, and urgency tactics. The awareness report created from this analysis can help businesses train their employees to recognize and avoid phishing attacks.

---

## Author

IGNAS EDD MALEWA  
CIN ID: FIT/APR26/CS8072  
Future Interns Cyber Security Internship (2026)

## Repository Link

https://github.com/Lewason/FUTURE_CS_02
