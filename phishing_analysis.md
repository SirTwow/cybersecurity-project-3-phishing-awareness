Phishing Awareness Analysis

Introduction

Phishing is a social engineering technique used to deceive people into revealing sensitive information, clicking malicious links, downloading harmful files, or making unauthorized payments.

This analysis demonstrates how suspicious messages can be examined using sender information, URLs, psychological triggers, and other red flags.

Example 1 — Fake Account Security Alert

Subject: Urgent: Your Account Will Be Suspended

Message:

«Your account has been flagged for unusual activity. You must verify your account within 30 minutes or access will be permanently suspended.

Click the link below to confirm your identity:

"https://decodelabs-security-login.com/verify"»

Red Flags

1. Urgency: The recipient is given only 30 minutes to act.
2. Threat of account suspension: Creates fear and pressure.
3. Suspicious domain: "decodelabs-security-login.com" imitates a legitimate organization.
4. Credential harvesting risk: The verification link may request login credentials.
5. No independent verification: The message encourages the user to click immediately.

Classification

MALICIOUS

Recommended Action

Block Domain & Escalate

Do not click the link or enter credentials. Report the message to the security team.

---

Example 2 — Fake Payment Request

Subject: Payment Required — Subscription Failed

Message:

«Your subscription payment could not be processed. Update your billing information immediately to prevent service interruption.

"https://service-billing-update.com"»

Red Flags

- Urgent payment request.
- Threat of service interruption.
- Suspicious billing domain.
- Request to provide payment information.
- Encourages immediate action without independent verification.

Classification

SUSPICIOUS

Recommended Action

Warn User & Verify

The user should access the service through its official application or website instead of using the provided link.

---

Example 3 — Suspicious QR Code Message

Subject: Security Verification Required

Message:

«Your account requires immediate security verification. Scan the QR code below to prevent account lockout.»

Red Flags

- Unexpected QR code.
- Account-lockout threat.
- Urgency.
- QR code hides the destination from normal desktop URL inspection.
- Requests security verification without prior context.

Classification

SUSPICIOUS

Recommended Action

Warn User & Verify

Do not scan the QR code until the request has been independently verified.

---

Analysis Method

For every suspicious message, check:

1. Sender identity and email address.
2. Reply-To and Return-Path information where available.
3. Domain and true root domain.
4. Links and their destinations.
5. Attachments.
6. Urgency and psychological pressure.
7. Requests for credentials, payment, or sensitive information.
8. Whether the request follows normal organizational procedures.

Final Triage Rule

SAFE → Close

SUSPICIOUS → Warn User & Verify

MALICIOUS → Block Domain & Escalate

Golden Rule

PAUSE → VERIFY → REPORT
