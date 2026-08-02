# 08 – Account Verification Request

## Purpose

This prompt generates a clear, professional, and security-focused email requesting that a customer verify their account. It helps businesses confirm a customer's identity while maintaining trust by explaining why verification is necessary, outlining the required steps, and reassuring customers that their information will be handled securely.

---

## Prompt

You are a professional Customer Support Representative.

Write a polite, professional, and reassuring email asking a customer to verify their account.

The email should:
- Greet the customer by name.
- Explain why account verification is required.
- Clearly outline the verification steps the customer should complete.
- Reassure the customer that their information will remain secure and confidential.
- Include a placeholder for the verification link.
- Encourage the customer to contact support if they need assistance.
- End with a courteous and professional closing.

Use a friendly, trustworthy, and security-conscious tone.

### Verification Information

- Customer Name: {{customer_name}}
- Reason for Verification: {{verification_reason}}
- Verification Link: {{verification_link}}
- Verification Deadline: {{verification_deadline}}
- Support Contact: {{support_contact}}

---

## Variables

| Variable | Description |
|----------|-------------|
| `{{customer_name}}` | Name of the customer |
| `{{verification_reason}}` | Reason verification is required |
| `{{verification_link}}` | Link to complete the verification process |
| `{{verification_deadline}}` | Date by which verification should be completed |
| `{{support_contact}}` | Customer support email or contact information |

---

## Why this prompt works

This prompt emphasizes clarity, trust, and security—three essential elements in account verification communications. It explains the purpose of the verification request without creating unnecessary concern, provides straightforward instructions, and reassures customers that their personal information will be protected. The reusable variables allow the prompt to be adapted for different verification scenarios while maintaining a consistent, professional tone.

---

## Example Input

**Customer Name:** Daniel Smith

**Reason for Verification:** We detected a login from a new device and need to confirm your identity.

**Verification Link:** https://example.com/verify-account

**Verification Deadline:** July 25, 2026

**Support Contact:** support@example.com

---

## Example Output

**Subject:** Please Verify Your Account

Hi Daniel,

To help keep your account secure, we need you to complete a quick verification process.

We recently detected a login from a new device and would like to confirm that it was you. This additional security step helps protect your account and personal information from unauthorized access.

Please complete your verification by **July 25, 2026** using the link below:

**https://example.com/verify-account**

The verification process only takes a few minutes, and your information will be handled securely and kept confidential.

If you have any questions or experience any issues during the verification process, please contact us at **support@example.com**. We'll be happy to assist you.

Thank you for helping us keep your account safe.

Best regards,

Customer Support Team

---

## Notes

- Replace all placeholder variables with the customer's actual verification details before generating the email.
- Clearly explain why verification is necessary to reduce customer confusion and build trust.
- Avoid requesting sensitive information directly in the email; instead, direct customers to a secure verification portal.
- This prompt can be adapted for identity verification, email confirmation, phone verification, account recovery, suspicious login activity, or compliance-related verification requests.
```
