# 04 – Delivery Delay Apology

## Purpose

This prompt generates a sincere, empathetic, and professional apology email when a customer's order has been delayed. It helps maintain customer trust by acknowledging the inconvenience, explaining the situation transparently, providing an updated delivery timeline, and reassuring the customer that the issue is being resolved.

---

## Prompt

You are a professional Customer Support Representative.

Write a polite, empathetic, and professional apology email to a customer whose order has been delayed.

The email should:
- Apologize sincerely for the delay.
- Acknowledge the inconvenience caused.
- Briefly explain the reason for the delay without placing blame.
- Provide an updated delivery estimate.
- Reassure the customer that their order is being monitored.
- Offer additional assistance if needed.
- End with a courteous and customer-focused closing.

Use a calm, reassuring, and customer-centric tone.

### Order Information

- Customer Name: {{customer_name}}
- Order Number: {{order_number}}
- Product: {{product_name}}
- Reason for Delay: {{delay_reason}}
- New Estimated Delivery Date: {{delivery_date}}

---

## Variables

| Variable | Description |
|----------|-------------|
| `{{customer_name}}` | Name of the customer |
| `{{order_number}}` | Customer's order number |
| `{{product_name}}` | Product or item purchased |
| `{{delay_reason}}` | Brief explanation for the shipping delay |
| `{{delivery_date}}` | Updated expected delivery date |

---

## Why this prompt works

This prompt encourages the AI to prioritize empathy before providing information about the delay. By guiding the model to apologize, acknowledge the customer's frustration, explain the situation clearly, and offer reassurance, it produces responses that feel genuine rather than robotic. The reusable variables also make it easy to adapt the prompt for different customers, products, and delivery scenarios while maintaining a consistent customer service tone.

---

## Example Input

**Customer Name:** Sarah Johnson

**Order Number:** #45827

**Product:** Wireless Noise-Cancelling Headphones

**Reason for Delay:** Unexpected shipping delays due to severe weather conditions.

**New Estimated Delivery Date:** July 22, 2026

---

## Example Output

**Subject:** Update on Your Order #45827

Hi Sarah,

Thank you for your patience. We're reaching out to sincerely apologize for the delay in delivering your **Wireless Noise-Cancelling Headphones**.

Unfortunately, unexpected weather conditions have affected our shipping schedule, and your order has taken longer than originally expected. We understand how disappointing delays can be, and we're truly sorry for the inconvenience.

The good news is that your order is currently in transit, and the updated estimated delivery date is **July 22, 2026**. Our team is closely monitoring the shipment to ensure it reaches you as quickly as possible.

We genuinely appreciate your understanding and patience while we work through this situation. If you have any questions or need further assistance, please don't hesitate to reply to this email—we're always happy to help.

Thank you for choosing us, and we look forward to delivering your order soon.

Best regards,

Customer Support Team

---

## Notes

- Replace the placeholder variables with the customer's actual order information before generating the email.
- Keep the explanation for the delay concise and avoid assigning blame to third parties.
- If compensation (such as a discount, refund, or store credit) is appropriate, add it after the delivery update.
- The prompt can be adapted for delays caused by weather, inventory shortages, high order volumes, customs processing, or carrier issues while maintaining a professional and empathetic tone.
