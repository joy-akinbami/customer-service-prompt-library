# 06 – Refund Request Response

## Purpose

This prompt generates a professional, empathetic, and solution-oriented email responding to a customer's refund request. It helps customer support teams acknowledge the customer's concern, communicate the refund decision clearly, explain the next steps, and maintain a positive customer relationship regardless of the outcome.

---

## Prompt

You are a professional Customer Support Representative.

Write a polite, empathetic, and professional email responding to a customer's refund request.

The email should:
- Thank the customer for contacting us.
- Acknowledge their concern with empathy.
- Clearly communicate whether the refund has been approved or declined.
- If approved, explain the refund amount, processing timeline, and payment method.
- If declined, briefly explain the reason while remaining respectful and offer an alternative solution if possible.
- Invite the customer to reach out with any additional questions.
- End with a courteous and customer-focused closing.

Use a calm, understanding, and professional tone.

### Refund Information

- Customer Name: {{customer_name}}
- Order Number: {{order_number}}
- Product or Service: {{product_or_service}}
- Refund Status: {{refund_status}}
- Refund Amount: {{refund_amount}}
- Refund Timeline: {{refund_timeline}}
- Reason (if applicable): {{reason}}

---

## Variables

| Variable | Description |
|----------|-------------|
| `{{customer_name}}` | Name of the customer |
| `{{order_number}}` | Customer's order number |
| `{{product_or_service}}` | Product purchased or service received |
| `{{refund_status}}` | Approved or declined |
| `{{refund_amount}}` | Amount being refunded (if approved) |
| `{{refund_timeline}}` | Estimated processing time |
| `{{reason}}` | Reason for approval, denial, or additional explanation |

---

## Why this prompt works

This prompt provides a clear structure for handling one of the most sensitive customer service scenarios. It begins with empathy, communicates the refund decision transparently, and explains the next steps in plain language. By including reusable variables, the prompt can handle both approved and declined refund requests while maintaining a consistent, professional tone that helps preserve customer trust.

---

## Example Input

**Customer Name:** Michael Adams

**Order Number:** #76391

**Product or Service:** Bluetooth Smart Speaker

**Refund Status:** Approved

**Refund Amount:** $89.99

**Refund Timeline:** 5–7 business days

**Reason:** The product arrived damaged during shipping.

---

## Example Output

**Subject:** Update on Your Refund Request

Hi Michael,

Thank you for contacting us regarding your recent order. We're sorry to hear that your **Bluetooth Smart Speaker** arrived damaged, and we appreciate you giving us the opportunity to resolve the issue.

We're pleased to let you know that your refund request has been **approved**. A refund of **$89.99** has been issued to your original payment method and should appear in your account within **5–7 business days**, depending on your financial institution.

We sincerely apologize for the inconvenience this experience has caused. Your satisfaction is important to us, and we're committed to providing a better experience in the future.

If you have any questions about your refund or need further assistance, please don't hesitate to reply to this email. We're always happy to help.

Thank you for your patience and understanding.

Kind regards,

Customer Support Team

---

## Notes

- Replace all placeholder variables with the customer's actual refund details before generating the email.
- For declined refund requests, provide a brief explanation based on company policy and, where appropriate, offer alternatives such as an exchange, replacement, repair, or store credit.
- Keep the explanation clear and respectful to avoid sounding defensive or dismissive.
- This prompt can be adapted for physical products, digital products, subscriptions, memberships, or service-based businesses while maintaining a professional and empathetic tone.
