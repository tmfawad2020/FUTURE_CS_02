# FUTURE_CS_02 — Phishing Detection & Awareness Report

**Future Interns Cyber Security Internship — Task 2**

## Executive Summary
This report implements the Future Interns phishing detection and awareness task. The supplied sample is classified as **PHISHING**.

## Sample Analysis

| Indicator | Observation | Risk |
|---|---|---|
| Urgency | Threat of permanent account lock within 24 hours | High |
| Generic greeting | “Dear User” | Medium |
| Suspicious link | secure-account-verify[.]com | High |
| Credential-verification lure | User is prompted to verify details | High |
| Impersonation | Message uses generic security-team authority language | Medium |

## Why It Is Phishing
Several strong indicators occur together: urgency/fear, an untrusted verification domain, generic wording, and a request related to account credentials. The safest response is not to click the link or provide information.

## Prevention Guidelines
1. Verify the sender independently.
2. Hover over links before opening them.
3. Do not use links supplied in suspicious messages for password resets.
4. Open the organisation's official website or application directly.
5. Be cautious of urgent threats, payment requests, password requests, OTP requests, and unexpected attachments.
6. Report suspicious messages to the organisation/security team.
7. Use multi-factor authentication.
8. Use a password manager and unique passwords.

## Safe / Suspicious / Phishing Rule
- **Safe:** trusted sender/domain, expected message, normal link destination, no suspicious pressure.
- **Suspicious:** unusual sender, unexpected request, unclear link, or inconsistent wording.
- **Phishing:** multiple strong indicators such as impersonation + urgency + malicious/suspicious link + credential lure.

## Evidence Note
The analysis is based on the Future Interns/public sample and does not claim a third-party sample as original work. Any additional sample should include source attribution and should be redacted before publication.

## Sources
- Future Interns Cyber Security Task 2
- https://github.com/rokibulroni/Phishing-Email-Dataset
- https://github.com/cw-l/email-corpus

Official task: https://futureinterns.com/cyber-security-task-2-2026/