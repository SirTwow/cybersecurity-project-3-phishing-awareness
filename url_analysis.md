Phishing URL & Domain Analysis

Purpose

This section explains how to identify suspicious URLs and deceptive domains commonly used in phishing attacks.

1. Check the True Root Domain

URLs can contain several subdomains designed to make a malicious website appear legitimate.

Example

"www.decodelabs.tech.login-update.com"

Read the domain from right to left.

- "www" → subdomain
- "decodelabs.tech" → misleading nested subdomain
- "login-update.com" → true root domain

Finding

The URL does not belong to DecodeLabs. The attacker is using the trusted-looking "decodelabs.tech" text to make the address appear legitimate.

Risk: High

---

2. Typosquatting

Attackers register domains that contain small spelling changes to trusted websites.

Example

Legitimate:

"paypal.com"

Suspicious:

"paypa1.com"

The letter l has been replaced with the number 1.

Risk: High

---

3. Combosquatting

Attackers add words to a legitimate brand name to create a deceptive domain.

Example

Legitimate:

"yourcompany.com"

Suspicious:

"yourcompany-secure-login.com"

The presence of the company name does not mean the domain is owned by that company.

Risk: High

---

4. Homoglyph Attacks

Attackers may use visually similar characters from other alphabets to make a fake domain look like a legitimate one.

This can make a malicious website difficult to distinguish from the real website.

Risk: High

---

5. Suspicious URL Indicators

Treat a URL with caution when it contains:

- Misspelled brand names.
- Unusual characters.
- Unexpected subdomains.
- Unrelated root domains.
- Suspicious words such as "secure", "verify", "login", or "update".
- URL shorteners hiding the destination.
- Unexpected login or payment pages.

URL Analysis Procedure

Before opening a suspicious link:

1. Pause and do not click.
2. Inspect the complete URL.
3. Identify the true root domain.
4. Compare it with the legitimate organization domain.
5. Look for spelling changes or deceptive subdomains.
6. If uncertain, verify the link through the organization's official website or another trusted channel.
7. Report confirmed or suspected phishing.

Conclusion

A trusted brand name appearing somewhere inside a URL does not prove that the website is legitimate.

Always identify the true root domain before trusting a link.

PAUSE → VERIFY → REPORT
