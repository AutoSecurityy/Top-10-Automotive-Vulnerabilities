<h1 align="center">
  Top 10 Automotive Vulnerabilities
</h1>
<p align="center">
  <strong>In Progress
</p>

<h2 align="center">
  About the Project
</h2>
As part of the <b>AutoSecurityy</b> community initiative, we are building a publicly available reference list linked to the OWASP's Top 10 — tailored specifically for automotive cybersecurity. This list aims to highlight the most commonly exploited and impactful vulnerabilities found across modern vehicle platforms with technical details, based on hands-on experience, practical testing, and community input.

---
No. | Vulnerability | Attack Example | Details
----|----|----|----|
1|Weak Vehicle Communication Protocols|CAN Bus Injection via OBD-II or Exposed Lines|When vehicles lack authentication on communications like CAN. Attackers can inject arbitrary frames via the OBD-II port or exposed in-vehicle wiring (e.g., behind lamps, infotainment units). This can lead to actions like unlocking doors, disabling braking systems, or spoofing sensor data.
2|Insecure Over-the-Air (OTA) Updates|Rogue FW Injection due to lack of proper authentication & encryption|Many vehicles lack strong protections for software updates. Weak hash validation, absence of rollback protection, or use of plain-text channels allows attackers to install tampered firmware or downgrade to known vulnerable versions.
3|Insecure Telematics Systems|Weak API security could access sensitive vehicle data or manipulate vehicle settings remotely.|APIs exposed by mobile apps, telematics servers, or companion web apps often suffer from IDORs, poor session control, or token leakage. Exploiting these allows remote attackers to control vehicle functions (lock/unlock, start engine) or exfiltrate user data.
4|Software Supply Chain Vulnerabilities|Arbitraty code execution into Infotainment systems|Third-party software components lelies by systems like Infotainment systems, vehicle SW updates, and applications may have known vulnerabilities that can be exploited to gain access into the systems or run arbitrary code.
5|Physical Access Exploits|Use of BadUSB, FW manipulation through USB & KiaBoys Hacks are few examples|Many attacks requires physical access to the vehicle to allow attackers to manipulate systems directly through interfaces like OBD-II & USB Ports, Settings in the Infotainment systems, or any other mean.
6|Inadequate Access Control Mechanisms|Charging Card Cloaning, Unauthorized access to remote diagnostic or FOTA server|Weak or poorly implemented access control measures into mobile apps, V2X communications, EV charging infra, and remote diagnostics can allow unauthorized access to vehicle systems, user information and admin privilege functions.
7|Poorly Implemented Authentication Mechanisms|Weak 0x27 security mechanism|Many automotive systems use weak authentication methods such as poor UDS security access mechanism, easily guessable passwords or hardcoded keys, making it easier for attackers to gain unauthorized access
8|Data Leakage and Privacy Violations| | |
9|Lack of Security in Integrated Systems| | |
10|Insecure Legacy Systems| | |

## Do the Contributions
We believe that with your experience and domain knowledge, your input for examples & details would be incredibly valuable in refining this effort.
+ Referece: https://cheatsheetseries.owasp.org/cheatsheets/Automotive_Security.html

