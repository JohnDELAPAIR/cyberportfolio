## 🛡️ Lab 1: Defensive Security Introduction
**Platform:** [TryHackMe](https://tryhackme.com/room/defensivesecurityintro)  
**Duration:** 20 mins | **Flag:** `THM{THREAT-BLOCKED}`  
**Skills:** SOC operations, DFIR workflow, blue team fundamentals

### What I Did
- Learned SOC (Security Operations Center) monitors threats 24/7
- Understood DFIR: investigate + contain cyber attacks  
- Discovered SIEM tools correlate logs to detect ransomware
- Got my first blue team defender badge

### Why This Matters For Tier 1 SOC
This is exactly what entry-level analysts do daily—understand alerts, follow triage process.


## 🐧 Lab 2: Linux Fundamentals Part 1
**Room:** [Linux Fundamentals Part 1](https://tryhackme.com/room/linuxfundamentalspart1)  
**Status:** ✅ **Completed** | **Duration:** 30 mins

**SOC Analyst Relevance:** Tier 1 analysts SSH into Linux servers daily:
- `grep` suspicious IPs in auth.log (brute force attacks)
- `find` new files by timestamp (malware drops)
- `ls -la` verify permissions on web servers

**Key Commands Mastered:**
```bash
ls -la                    # List files with permissions  
cd /var/log              # Navigate to log directory
grep "failed" auth.log   # Find failed login attempts
cat /var/log/syslog      # Read system logs
head -20 auth.log        # First 20 lines of log file
tail -f auth.log         # Live log monitoring

```
**What This Means For SOC Work:**
- Can investigate Linux log files for Indicators of Compromise (IOCs)
- Ready to analyze authentication failures, web server access logs

![Linux Fundamentals Pt 1 Complete]

  1<img width="1018" height="659" alt="Linux pt1" src="https://github.com/user-attachments/assets/7c51cc0c-858e-4cf1-b149-832ad04533b2" />
