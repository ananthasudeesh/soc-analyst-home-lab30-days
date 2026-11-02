# Day 02 – SOC Fundamentals

**Status:** Learning Completed | Practical Validation & Quiz Pending

## 🎯 Objective

Understand the fundamental concepts, responsibilities, and terminology used by Security Operations Center (SOC) Analysts.

## 📚 Topics Covered

### 1. Security Operations Center (SOC)
A centralized team responsible for monitoring, detecting, analyzing, and responding to cybersecurity threats.

### 2. Security Event
An observable activity or action occurring within a system, application, or network.

### 3. Security Log
A recorded entry containing information about system activities and events.

### 4. Security Alert
A notification generated when activity matches a detection rule or suspicious condition.

### 5. Security Incident
A security event or series of events assessed as requiring investigation and response.

### 6. Indicator of Compromise (IOC)
An observable indicator that may suggest malicious activity, such as suspicious IP addresses, file hashes, or domains.

### 7. Security Information and Event Management (SIEM)
A platform that collects, centralizes, correlates, and analyzes security logs to help identify suspicious activities.

## 🔬 Practical Exercise – Authentication Log Analysis

Created a synthetic authentication log and analyzed it using Linux commands.

**Commands used:**

```bash
cat auth.log
grep "Failed login" auth.log
grep -c "Failed login" auth.log
```

**Exercise objectives:**

- Inspect authentication records.
- Identify failed login attempts.
- Count failed authentication events.
- Understand suspicious login patterns.

## 🔍 Security Observation

Repeated failed login attempts followed by a successful login may indicate suspicious authentication activity.

However, this pattern alone does not confirm an attack. Additional investigation is necessary, including:

- Source IP address analysis.
- Login timestamps.
- Username verification.
- Successful login details.
- Supporting system and network logs.

## 💡 Key Learnings

- Understand the difference between events, logs, alerts, and incidents.
- Learn the purpose of SIEM platforms.
- Understand the role of IOCs in threat detection.
- Recognize suspicious authentication patterns.
- Understand why security alerts require investigation.

## 🚀 Next Session – Day 03

**Topic: Authentication Log Analysis**

Planned activities:

- Understand authentication log structure.
- Analyze timestamps and usernames.
- Identify source IP addresses.
- Differentiate successful and failed logins.
- Investigate suspicious authentication patterns.

---

**Project:** 30-Day SOC Analyst Home Lab  
**Day:** 02/30  
**Environment:** Kali Linux
Author: Anantha Sudeesh SD

🔐 Learn | Monitor | Detect | Investigate | Defend
