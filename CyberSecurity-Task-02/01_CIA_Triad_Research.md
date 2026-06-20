# Part A: Understanding the CIA Triad

The CIA Triad — Confidentiality, Integrity, and Availability — is the foundational model used to guide security policy and evaluate how well information is protected. Every security control, in some way, maps back to preserving one or more of these three principles.

## 1. Confidentiality

**Definition:** Confidentiality means ensuring that information is accessible only to those who are authorized to view it, and protected from unauthorized access or disclosure.

**Why it is important:** Without confidentiality, sensitive data — personal information, financial records, trade secrets, medical history — can be exposed to people who shouldn't have access to it. This can lead to identity theft, financial fraud, reputational damage, and loss of competitive advantage.

**Real-world Example:** When a hospital encrypts patient records and restricts access to only authorized doctors and staff, it's protecting confidentiality. A breach occurs when, for example, an unauthorized party gains access to a database of patient records, exposing private medical history.

## 2. Integrity

**Definition:** Integrity means ensuring that information is accurate, complete, and has not been altered or tampered with by unauthorized parties, whether intentionally or accidentally.

**Why it is important:** If data integrity is compromised, decisions based on that data become unreliable. In critical systems like banking, healthcare, or examination records, even small unauthorized changes can cause serious harm — incorrect medical dosages, falsified financial records, or altered grades.

**Real-world Example:** A student hacking into a college's database to change their own exam grades is a direct attack on integrity — the data wasn't stolen, but it was tampered with so it no longer reflects the truth.

## 3. Availability

**Definition:** Availability means ensuring that information and systems are accessible to authorized users whenever they're needed, without unnecessary downtime or disruption.

**Why it is important:** Even perfectly confidential and accurate data is useless if it can't be accessed when needed. Businesses, hospitals, and critical infrastructure depend on systems being available around the clock; downtime can mean lost revenue, delayed medical care, or operational chaos.

**Real-world Example:** A Distributed Denial of Service (DDoS) attack that floods a college's website with traffic, making it crash and become inaccessible during exam registration, is a direct attack on availability.

## Comparison Table

| Principle | Definition | Importance | Real-World Example |
|---|---|---|---|
| **Confidentiality** | Only authorized users can access information | Prevents data theft, fraud, and privacy violations | Hospital restricting patient records to authorized staff only |
| **Integrity** | Information remains accurate and unaltered | Ensures trustworthy, reliable data for decisions | Student hacking a database to alter their exam grades |
| **Availability** | Systems and data are accessible when needed | Prevents downtime and disruption to critical operations | DDoS attack crashing a college website during registration |
