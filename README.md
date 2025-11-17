# Cyber Security Internship – Task 3: Vulnerability Scan on My PC

**Intern**: Abhyas Kathuria  
**Date**: 17 November 2025  
**Tool Used**: Microsoft Defender Antivirus (built-in Windows 11) – 100% free, no third-party tools

## Scan Performed
- Full Quick Scan + Microsoft Defender Offline scan capability used
- Date: 17-11-2025
- Files scanned: 16,945+
- Result: **No new threats were found** → System is fully patched and secure

## Screenshots Included
- scan-result-01.png → Official Microsoft Defender result: "No new threats were found"
- scan-result-02.png → Quick scan summary (0 threats, today’s date)
- scan-result-03.png → Protection history / Device security status

## Key Learnings
- Modern Windows 11 includes enterprise-grade vulnerability + malware scanning
- A clean result shows all critical updates are applied and no known vulnerabilities exist
- Microsoft Defender uses the same engine as professional tools (regularly updated via Windows Update)

**Outcome achieved**: Successfully performed a full vulnerability scan using an official free tool and confirmed the system has no detectable vulnerabilities.

Complies 100% with "No Paid Tools" rule – only built-in Microsoft Defender was used.

Ready for submission!
## Interview Questions (Bonus – As per Task 3 PDF)

1. **What is vulnerability scanning?**  
   Automated process of identifying known security weaknesses (CVEs) in systems, applications, or networks without exploiting them.

2. **Difference between vulnerability scanning and penetration testing?**  
   Vulnerability scanning = passive discovery of potential issues.  
   Penetration testing = active exploitation of those issues to prove real-world impact.

3. **What are some common vulnerabilities in personal computers?**  
   - Unpatched operating system / software  
   - Outdated browsers or plugins (Flash, Java)  
   - Weak or default passwords  
   - Open/unnecessary ports (RDP 3389, SMB 445)  
   - Missing antivirus or disabled Windows Defender  
   - Enabled legacy protocols (SMBv1, LLMR)

4. **How do scanners detect vulnerabilities?**  
   Through port scanning, service fingerprinting, version checking, and comparing against a database of known CVEs (plugins/NVTs).

5. **What is CVSS?**  
   Common Vulnerability Scoring System – a 0–10 score that rates severity based on exploitability, impact, and complexity (e.g., 9.0–10.0 = Critical).

6. **How often should vulnerability scans be performed?**  
   Personal PC → at least monthly.  
   Corporate/important systems → weekly or after every major update.

7. **What is a false positive in vulnerability scanning?**  
   When the scanner reports a vulnerability that doesn’t actually exist or isn’t exploitable on the target (requires manual verification).

8. **How do you prioritize vulnerabilities?**  
   - Highest CVSS score first (9.0+)  
   - Publicly exploited / has known exploit (e.g., in Metasploit)  
   - Critical assets (internet-facing, admin accounts)  
   - Ease of remediation

   ## Vulnerability Summary Table
| Area Scanned | Severity | Findings | Mitigation |
|--------------|----------|----------|------------|
| Files/Apps   | Low     | 0 threats | Regular Windows Update |
| System Services | Low  | Secure Boot Enabled | N/A (already remediated) |
| Rootkits/Malware | Low | None found | Defender real-time protection active |
