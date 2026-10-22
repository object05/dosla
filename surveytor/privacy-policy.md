---
title: Privacy Policy — Surveytor
---

# Privacy Policy — Surveytor

**Status:** draft for legal review — not yet in effect
**Effective date:** [DATE OF PUBLICATION]
**Data controller:** DOSLA d.o.o., Trg Dušana Kvedra 13, 2000 Maribor, Slovenia, registration number (matična številka) 5821053000, tax number (davčna številka) 52566439 ("**DOSLA**", "**we**", "**us**")
**Contact for privacy requests:** hblockdev@gmail.com

This policy explains what personal data Surveytor (the "**Service**", at [DOMAIN]) collects, why, who we share it with, how long we keep it, and what rights you have. It follows the EU General Data Protection Regulation (Regulation (EU) 2016/679, "**GDPR**"), the Slovenian Personal Data Protection Act (ZVOP-2) and, for users in the United Kingdom, the UK GDPR.

We have not appointed a data protection officer, as the law does not require one for our processing. Write to the address above with any question.

---

## 1. The short version

- We collect what we need to run your account and your mock runs: your email address, your password (only as a one-way hash), what you upload, what the Service generates for you, your purchases, and basic security logs.
- Your uploaded surveys are sent to Anthropic's Claude AI model to read the questions and write the synthetic answers. Anthropic does not use them to train its models.
- The respondents Surveytor generates are invented. They are not real people and no real person's answers are used to make them.
- We don't sell your data, show ads, or use advertising or tracking cookies. Our visitor statistics are self-hosted and cookieless.
- Payments go through Stripe. We never see or store your card number.
- You can download everything we hold about you and delete your account yourself, from the account page.

## 2. What we collect, why, and on what legal basis

| What | Why | Legal basis (GDPR Art. 6(1)) |
|---|---|---|
| **Account data**: email address, password hash (Argon2; we never store or see your password), whether your email is verified, your name and organisation if you enter them (optional), your Google account ID, name and email if you sign in with Google, and when you accepted the Terms of Service (and which version) | To create and run your account and sign you in | (b) performing our contract with you |
| **Sessions**: sign-in sessions with the browser and device description (user agent) | To keep you signed in, let you see and end your sessions, and sign you out everywhere after a password change | (b) contract; (f) legitimate interest in account security |
| **Your content**: survey documents you upload (PDF/DOCX), the text and questions extracted from them, your edits, the configuration of each run, the generated synthetic respondents and answers, and the results and exports | To provide the Service: reading your survey, generating mock runs, showing results, making exports | (b) contract |
| **Purchases**: what you bought, when, the amount and currency, Stripe's payment and session identifiers, your token balance and how tokens were spent or refunded | To sell and deliver tokens, handle refunds and disputes, and meet tax and accounting duties | (b) contract; (c) legal obligation (tax and accounting law) |
| **Security and abuse prevention**: the IP address and time of sign-ins, sign-ups, password resets, purchases and account deletions; counters of failed attempts; the networks your account signed in from in the last 90 days; whether a new account's email is the same mailbox as an earlier account (for example a "+tag" or Gmail dot alias); a one-way hash of the email of a deleted account that had used its free run | To protect accounts from password guessing and takeover, and to stop the one free run per person being claimed again and again | (f) legitimate interest in keeping the Service secure and its free run fair |
| **Error reports**: technical details of a crash or error, from our servers and your browser (no form contents; we switched off sending your IP address and cookies with them) | To find and fix bugs | (f) legitimate interest in a working Service |
| **Server logs**: requests to our servers, which include your IP address | Security and troubleshooting | (f) legitimate interest |
| **Visitor statistics**: pages viewed, referrer, browser type, country, collected by our self-hosted Umami without cookies; Umami doesn't store your IP address | To see how the site is used and improve it | (f) legitimate interest |
| **Emails we send you**: verification, password reset, purchase confirmations and similar | To run your account and confirm purchases | (b) contract; (c) legal obligation for purchase confirmations |
| **Messages you send us** | To answer you | (b) contract or (f) legitimate interest |

Where we rely on legitimate interest, we have weighed it against your interests and rights, and kept the data to the minimum and for the shortest time that does the job (see section 5). You can object to it (section 7).

We don't send marketing emails. If we ever want to, we'll ask first.

**Do you have to give us this data?** Your email address and a password (or a Google sign-in) are needed to have an account, and payment details are needed to buy tokens. Everything else is either generated by using the Service or optional.

## 3. Uploaded surveys and the AI

When you upload a survey, we extract its text and send it to Anthropic's Claude model (see section 4) to identify the questions. When you start a mock run, we send the questions, and each synthetic respondent's invented profile and answers, to Claude to write the open-text answers and to work out how the questions relate.

- **Don't put personal data in your surveys** unless you need to. A blank questionnaire normally contains none. If your document does contain personal data (for example names in an example answer), you are responsible for having a legal basis to share it with us, and we process it only on your instructions. For business customers, our Data Processing Agreement ([link]) covers this.
- **The synthetic respondents are invented.** Their demographics and opinions are drawn at random from statistical distributions. They are not based on, and do not describe, any real person, and we don't create profiles of you or anyone else from your data.
- **No automated decisions about you.** We don't make decisions about you based solely on automated processing that have legal or similarly significant effects (GDPR Art. 22). The alias check in section 2 only decides whether a new account gets a free run; if you think it got it wrong, write to us and a person will look at it.
- **AI output is labelled.** Exports are marked as AI-generated synthetic data, as the EU AI Act requires (Regulation (EU) 2024/1689, Art. 50).

## 4. Who we share data with

We don't sell your personal data or share it for advertising. We use these service providers ("**processors**"), each bound by a data processing agreement, only for the purposes above:

| Provider | What for | Where | Transfer safeguard |
|---|---|---|---|
| **Contabo GmbH** (Munich, Germany) | Hosts our servers and the database | Germany (EU) | Inside the EU |
| **Anthropic, PBC** (USA) | Claude AI model: reads uploaded surveys and writes synthetic answers. Under Anthropic's commercial terms it doesn't train on this content and keeps it only for a limited time (currently [7 / 30 — VERIFY] days) for safety and abuse checks | USA | EU Standard Contractual Clauses in Anthropic's data processing addendum [VERIFY whether Anthropic is also certified under the EU–US Data Privacy Framework] |
| **[Backup storage provider — TO CHOOSE]** | Encrypted off-site backups | [EU — TO CONFIRM] | [—] |

Some providers act as independent controllers under their own privacy policies:

- **Stripe** (Stripe Payments Europe, Ltd., Ireland, and its affiliates) processes your payment and fraud checks when you buy tokens. See [stripe.com/privacy](https://stripe.com/privacy). Stripe may transfer data to the USA under the EU–US Data Privacy Framework and Standard Contractual Clauses.
- **Google** (Google Ireland Limited) if you choose "Continue with Google". Google's sign-in script is loaded only when you click that button; it then receives your IP address and browser details, and your Google account details if you sign in. See [policies.google.com/privacy](https://policies.google.com/privacy).

We may also disclose data when the law requires it (for example to tax authorities or under a court order), to protect our rights or others' safety, or to a successor if DOSLA's business is sold or merged, under this policy.

Our error tracking (GlitchTip), statistics (Umami), logging and email are self-hosted on our own servers. No third party receives that data.

## 5. How long we keep data

| Data | Kept for |
|---|---|
| Account data, your content, sessions in use | Until you delete your account (or the content). Deleting a survey removes its document, questions and runs |
| Ended sessions, used or expired reset and verification links | 30 days after they stop working |
| Security log entries (with IP address) | 12 months |
| Server logs | 30 days |
| Error reports | 90 days |
| Networks an account signed in from | 90 days |
| Failed sign-in counters | Up to 1 hour |
| Hash of a deleted account's email, when its free run was used | 2 years after deletion. A one-way hash: it can only confirm an email we're shown again, not reveal one |
| Purchase records | Your account's purchase history is deleted with your account. The records tax and accounting law require (invoices and Stripe's payment records) are kept as long as that law requires, in Slovenia generally 10 years [VERIFY with accountant] |
| Backups | Up to 6 months, then overwritten. Data you delete leaves our backups within that time |
| Visitor statistics | Aggregated and anonymous; kept indefinitely |

When you delete your account, we delete your account data, content, runs, sessions, token balance and security log entries straight away, except the email hash above and records we must keep by law.

## 6. Cookies and similar technologies

We only use what's needed for the Service to work, so we don't ask for consent (ePrivacy Directive Art. 5(3), Slovenian ZEKom-2):

- `st_access`, `st_refresh`: your sign-in session (httpOnly, first-party). With "Keep me signed in" they last 30 minutes and 30 days, and are renewed; without it they end when you close the browser (`st_session_only` marks that choice).
- Your light or dark mode choice, stored in your browser's local storage.

Umami statistics don't use cookies or local storage. If you click "Continue with Google", Google's sign-in may set or read Google's own cookies; see Google's policy above.

## 7. Your rights

You have the right to:

- **Access** your data and get a copy: download it any time from Account → Export my data, or ask us.
- **Correct** inaccurate data: change your name and organisation on the account page; to change your email address, ask us.
- **Delete** your data: delete your account from the account page, or ask us.
- **Portability**: get the data you gave us in a machine-readable form (your exports and the account export).
- **Restrict** our processing, or **object** to processing based on legitimate interest. We'll stop unless we have compelling legitimate grounds, or need it for legal claims.
- **Withdraw consent** where we asked for it, without affecting what we did before.
- **Complain** to a data protection authority: in Slovenia, the Information Commissioner (Informacijski pooblaščenec, Dunajska cesta 22, 1000 Ljubljana, [www.ip-rs.si](https://www.ip-rs.si)), or the authority where you live or work. UK users can complain to the ICO ([ico.org.uk](https://ico.org.uk)). We'd appreciate the chance to fix it first.

Write to hblockdev@gmail.com from the email address on your account (so we know it's you). We'll answer within one month, which can be extended by two months for complex requests, and we'll tell you if it is. It's free unless a request is clearly unfounded or excessive.

**California residents:** we don't sell or share personal information as the CCPA defines those terms, and we don't use sensitive personal information to infer characteristics. You can ask what we hold and ask us to delete or correct it, as above.

## 8. Security

Passwords are stored only as Argon2 hashes; sessions use short-lived tokens that can be revoked; the site is served over HTTPS only; our admin tools and databases aren't reachable from the internet; backups are encrypted; and access is limited to the people who run the Service. No system is perfectly secure. If a breach puts your rights at risk, we'll tell the authority within 72 hours and tell you without undue delay, as the GDPR requires.

## 9. Age

Surveytor is for people aged 18 or older. We don't knowingly collect data from children. If you think a child has given us data, write to us and we'll delete it.

## 10. Changes

We'll post changes here with a new effective date. For material changes, we'll email you at least 30 days before they apply.

## 11. Contact

DOSLA d.o.o.
Trg Dušana Kvedra 13, 2000 Maribor, Slovenia
hblockdev@gmail.com

See also the [Terms of Service](./terms-of-service.html).
