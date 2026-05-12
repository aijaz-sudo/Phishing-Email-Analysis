# Initial Analysis

## Suspicious Indicators

### 1. Fake Sender Domain
The email uses a suspicious domain:
microsoft365-support.com

Legitimate Microsoft emails normally come from:
- microsoft.com
- office.com

### 2. Urgency Tactic
The attacker creates panic using:
"Password expires today"

This pressures the victim to act quickly.

### 3. Suspicious URL
The email contains:
http://microsoft365-login-security-alert.com

The URL appears to impersonate Microsoft services.

### 4. Threatening Language
The email threatens account suspension within 24 hours.

This is a common phishing technique.

---

# Possible Attack Type
Credential Phishing

# Risk Level
HIGH




## Header Analysis Findings

- SPF check failed
- DKIM check failed
- DMARC authentication failed
- Possible sender spoofing detected
- Suspicious sender infrastructure identified

## VirusTotal Analysis

The phishing URL was analyzed using VirusTotal.

Observations:
- URL reputation checked
- Domain appears suspicious/inactive
- Threat intelligence correlation performed

Conclusion:
The URL is potentially malicious and associated with phishing activity.

## URLScan.io Analysis

The phishing domain was analyzed using URLScan.io.

Observations:
- DNS resolution failed
- Domain could not be resolved
- Infrastructure appears inactive or simulated

Possible Explanation:
- Domain taken down
- Expired malicious infrastructure
- Simulated phishing environment

Conclusion:
The domain remains suspicious despite inactive status.

## AbuseIPDB Analysis

The sender IP address was investigated using AbuseIPDB.

IP Address:
185.199.110.153

Observations:
- IP reputation checked
- Infrastructure information reviewed
- Abuse reports analyzed

Conclusion:
The IP address is potentially associated with suspicious email activity.



## WHOIS Analysis

The phishing domain was investigated using WHOIS lookup.

Observations:
- Domain registration information checked
- Infrastructure ownership reviewed
- Domain appears inactive or simulated

Possible Explanation:
- Expired phishing infrastructure
- Removed malicious domain
- Simulated phishing environment

Conclusion:
The domain remains suspicious despite limited WHOIS information.




## IOC Extraction

The following Indicators of Compromise (IOCs) were identified:

- Suspicious phishing domain
- Malicious URL
- Suspicious sender email
- Sender infrastructure IP address

The extracted IOCs were documented in iocs.csv for future detection and investigation activities.