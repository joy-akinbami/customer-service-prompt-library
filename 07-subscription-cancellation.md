# 07 – Subscription Cancellation

## Purpose

This prompt generates a professional, empathetic, and respectful email confirming a customer's subscription cancellation. It acknowledges the customer's decision without applying unnecessary pressure, confirms the cancellation details, explains what happens next, and leaves the door open for the customer to return in the future.

---

## Prompt

You are a professional Customer Support Representative.

Write a polite, empathetic, and professional email confirming a customer's subscription cancellation.

The email should:
- Thank the customer for being a valued subscriber.
- Confirm that their subscription cancellation has been processed.
- State when their access or subscription benefits will end.
- Briefly explain what happens after cancellation (such as billing or account access).
- Express appreciation for their past business.
- Invite them to return in the future or contact support if they have any questions.
- End with a warm and professional closing.

Use a respectful, appreciative, and customer-focused tone.

### Subscription Information

- Customer Name: {{customer_name}}
- Subscription Plan: {{subscription_plan}}
- Cancellation Date: {{cancellation_date}}
- Access Ends: {{access_end_date}}
- Support Contact: {{support_contact}}

---

## Variables

| Variable | Description |
|----------|-------------|
| `{{customer_name}}` | Name of the customer |
| `{{subscription_plan}}` | Name of the subscription or membership plan |
| `{{cancellation_date}}` | Date the cancellation was processed |
| `{{access_end_date}}` | Date the customer's subscription benefits end |
| `{{support_contact}}` | Customer support email or contact information |

---

## Why this prompt works

This prompt balances professionalism with empathy by respecting the customer's decision while providing all the essential information about their cancellation. It clearly confirms the cancellation, sets expectations regarding future billing and account access, and maintains goodwill by thanking the customer and inviting them to return. The reusable variables make the prompt suitable for SaaS products, streaming services, memberships, online courses, and subscription-based businesses.

---

## Example Input

**Customer Name:** Olivia Martinez

**Subscription Plan:** Premium Business Plan

**Cancellation Date:** July 18, 2026

**Access Ends:** August 18, 2026

**Support Contact:** support@example.com

---

## Example Output

**Subject:** Your Subscription Has Been Cancelled

Hi Olivia,

Thank you for being a valued subscriber to our **Premium Business Plan**.

This email confirms that your subscription cancellation has been successfully processed as of **July 18, 2026**. You'll continue to enjoy all the benefits of your current plan until **August 18, 2026**, after which your subscription will expire and no further charges will be made.

We appreciate the opportunity to have served you and are grateful for your support. While we're sorry to see you go, we understand that your needs may change, and we'd be delighted to welcome you back whenever you're ready.

If you have any questions about your account or need assistance before your subscription ends, please don't hesitate to contact us at **support@example.com**.

Thank you once again, and we wish you all the best.

Warm regards,

Customer Support Team

---

## Notes

- Replace the placeholder variables with the customer's actual subscription details before generating the email.
- Clearly communicate when billing stops and when access to the service ends to avoid confusion.
- Keep the tone appreciative and avoid using overly persuasive language that may make the customer feel pressured to stay.
- This prompt can be adapted for software subscriptions, memberships, online learning platforms, streaming services, newsletters, or any recurring subscription business.
