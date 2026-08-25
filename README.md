Project 3: Phishing Awareness Analysis & Triage Toolkit

DecodeLabs Industrial Training Kit — Batch 2026

Objective

This project focuses on identifying and analysing phishing attempts through technical indicators, social engineering tactics, suspicious links, and communication anomalies.

The goal is to build a practical phishing triage toolkit that helps non-expert users recognize suspicious messages and take the correct action.

Core Principle

PAUSE → VERIFY → REPORT

Users should stop interacting with suspicious messages, verify unusual requests through a trusted secondary channel, and report suspected phishing attempts to the appropriate security team.

Phishing Red Flag Checklist

- Sender display name does not match the actual email address.
- Suspicious, misspelled, or lookalike domains.
- Links lead to unexpected or unrelated domains.
- Urgent requests demanding immediate action.
- Requests for passwords, MFA codes, banking details, or other sensitive information.
- Unexpected or dangerous attachments.
- Fake forwarded email chains or unusual conversation history.
- Requests to bypass normal security or approval procedures.
- Suspicious QR codes requesting account verification or payment.
- Unexpected phone numbers or callback instructions.
- Repeated or unexpected MFA approval requests.
- Messages using authority, fear, curiosity, greed, or urgency to influence the recipient.

Header & URL Analysis

When analysing a suspicious email, inspect:

- From address
- Reply-To address
- Return-Path
- Sender domain
- True/root domain
- Subdomains
- Link destinations
- Lookalike or typosquatted domains

A URL such as "www.decodelabs.tech.login-update.com" should be treated with caution because the actual root domain is login-update.com, not decodelabs.tech.

Phishing Classification

Safe

No significant phishing indicators are identified.

Action: Close

Suspicious

One or more unusual indicators are present, but malicious intent cannot yet be confirmed.

Action: Warn User and verify the request

Malicious

Strong evidence indicates phishing, credential harvesting, malware delivery, impersonation, or another malicious objective.

Action: Block Domain & Escalate

Phishing Triage Decision Tree

Incoming Suspicious Email

↓

Check Sender, Headers and URL

↓

Are there suspicious indicators?

- No → SAFE → Close
- Yes → Continue analysis

↓

Is the activity potentially malicious?

- No/Uncertain → SUSPICIOUS → Warn User & Verify
- Yes → MALICIOUS → Block Domain & Escalate

Human Firewall Rule

PAUSE

Stop interacting with the message and recognize possible psychological triggers such as urgency, fear, or authority.

VERIFY

Confirm the request through a trusted secondary communication channel.

REPORT

Report the suspicious message to the appropriate security team instead of simply deleting it.

Common Phishing Types

- Mass Phishing: High-volume generic phishing campaigns.
- Spear Phishing: Targeted attacks using personal or organizational information.
- Whaling: Attacks targeting executives or other high-value individuals.
- Smishing: Phishing through SMS or text messages.
- Vishing: Phishing through voice calls.
- Quishing: Phishing using malicious QR codes.
- Search Engine Phishing: Lookalike malicious websites promoted through manipulated search results.

Conclusion

Phishing attacks exploit the gap between technical security controls and human decisions. By checking sender information, headers, URLs, psychological triggers, and suspicious communication patterns, users can identify threats before they result in compromise.

The key defensive process is:

PAUSE → VERIFY → REPORT
