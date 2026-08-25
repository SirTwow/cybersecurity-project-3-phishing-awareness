Phishing Triage Decision Tree

Purpose

This decision tree provides a simple process for determining how to respond to an incoming suspicious email or message.

Step 1 — Check the Sender

Does the sender's email address match the organization or person they claim to represent?

- Yes → Continue to Step 2.
- No → Treat as suspicious and continue checking.

Step 2 — Check the URL

Does the link lead to the expected legitimate domain?

- Yes → Continue to Step 3.
- No → Treat as suspicious or potentially malicious.

Check carefully for:

- Misspelled domains
- Lookalike domains
- Suspicious subdomains
- Unrelated root domains
- Shortened or hidden links

Step 3 — Check the Request

Does the message request sensitive information, payment, credentials, MFA approval, or an unusual action?

- No → Continue to Step 4.
- Yes → Treat as suspicious and verify independently.

Step 4 — Check Psychological Pressure

Look for:

- Urgency
- Fear
- Authority
- Curiosity
- Greed or unexpected rewards

Are these being used to pressure the recipient?

- No → Continue to Step 5.
- Yes → Treat as suspicious.

Step 5 — Determine the Outcome

SAFE

No significant suspicious indicators are identified.

Action: Close

SUSPICIOUS

One or more warning signs are present, but malicious intent has not been confirmed.

Action: Warn User & Verify

MALICIOUS

Strong indicators show that the message is designed to steal information, deliver malware, impersonate a trusted person, or cause financial or security harm.

Action: Block Domain & Escalate

Final Process

Incoming Message

↓

Check Sender + Headers + URL

↓

Check Request + Attachments + Psychological Triggers

↓

SAFE → Close

SUSPICIOUS → Warn User & Verify

MALICIOUS → Block Domain & Escalate

Golden Rule

PAUSE → VERIFY → REPORT

Never click, reply, download, scan, or provide sensitive information before a suspicious request has been properly verified.
