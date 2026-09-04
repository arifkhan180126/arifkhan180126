# Abdur Rahim

### SOC Analyst | Threat Detection | Log Analysis | Python Security Automation

I investigate suspicious activity, turn raw logs into clear security findings, and build practical tools that help identify threats early. My work is grounded in a simple principle: understand normal behavior, detect meaningful deviations, and communicate the risk clearly enough for action.

I am focused on blue-team security, especially authentication monitoring, brute-force detection, incident triage, and repeatable analysis with Python.

---

## Security Focus

- **Security Monitoring:** Reviewing authentication events and identifying suspicious patterns
- **Threat Detection:** Building threshold- and behavior-based detection logic
- **Log Analysis:** Extracting useful indicators such as source IPs, users, timestamps, and event types
- **Incident Triage:** Separating actionable signals from routine activity
- **Python Automation:** Turning repetitive SOC tasks into reliable scripts
- **Security Reporting:** Presenting findings in a concise, investigation-ready format

## Technical Toolkit

```text
Security Operations  → Log Analysis · Alert Triage · Brute-Force Detection · IOC Review
Programming          → Python · Data Parsing · Automation · Counter-based Aggregation
Platforms             → GitHub · Windows · Linux
Core Knowledge        → Authentication Events · Network Fundamentals · Incident Response
Workflow              → Observe · Validate · Investigate · Document · Improve
```

## Featured Project

### [SOC Failed Login Analyzer](https://github.com/arifkhan180126/Abdur-Rahim)

A Python-based detection project that analyzes authentication logs, groups failed login attempts by source IP, and raises an alert when an address reaches three or more failures.

**What the project demonstrates:**

- Parsing structured security events
- Filtering successful and failed authentication activity
- Aggregating failures by source IP
- Applying a configurable alert threshold
- Producing analyst-friendly console output
- Writing clean, reusable Python functions

```text
=== Failed Login Report ===
10.0.0.15: 1 failed attempt(s)
192.168.1.10: 4 failed attempt(s)
[ALERT] Possible brute-force attack from 192.168.1.10 (4 failed attempts)
```

## How I Approach an Investigation

1. **Establish context** — identify the affected account, source, timestamp, and event type.
2. **Validate the signal** — confirm the event is not expected behavior or a parsing error.
3. **Look for patterns** — compare frequency, repetition, timing, and related indicators.
4. **Assess impact** — determine whether access succeeded and what may be affected.
5. **Document clearly** — record evidence, conclusions, and recommended next actions.
6. **Improve detection** — turn investigation lessons into better monitoring logic.

## Current Direction

I am continuing to build hands-on projects around:

- Real log-file ingestion and command-line analysis
- Windows authentication and Sysmon event investigation
- SIEM-style searches and detection rules
- IP enrichment and indicator correlation
- Alert severity and false-positive reduction
- Incident reports and investigation timelines

## Professional Mindset

I value careful validation over quick assumptions. A useful security alert should be explainable, reproducible, and connected to a clear response action. I write code and documentation with that same standard: readable, testable, and designed for the next analyst who needs to use it.

---

<p align="center">
  <strong>Open to SOC, blue-team, and cybersecurity collaboration.</strong><br>
  Explore my repositories to see the projects I am building and improving.
</p>
