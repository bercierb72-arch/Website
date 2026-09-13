---
title: Pay from a QR code
subtitle: Scan a Bitcoin address or Lightning invoice to make a payment
tags: [usage, featured]
---

BlueWallet can pay from a scanned QR code instead of manual typing. This works for both **on-chain Bitcoin addresses** and **Lightning invoices**.

## Open the right wallet

From the home screen, open the wallet you want to pay from:

- Use a **Bitcoin wallet** for on-chain payments.
- Use a **Lightning wallet** for Lightning invoices.

{% include phone-screenshot-image.html img="send-bitcoin-01-wallet.png" alt="Bitcoin wallet with Send and Receive buttons" %}

Tap **Send** at the bottom of the screen.

## Scan the QR code

On the send screen, tap the scan button and point the camera at the recipient's QR code.

BlueWallet reads the QR and fills in the payment details automatically when possible:

- **Bitcoin address QR:** fills the recipient address.
- **Bitcoin payment request (BIP21):** fills the address and may also include an amount or label.
- **Lightning invoice:** fills the invoice and any amount already encoded in it.

{% include phone-screenshot-image.html img="send-bitcoin-02-send-details.png" alt="Send screen ready for a scanned payment" %}

## Review the details

Before sending, check that:

- the wallet type matches the QR you scanned
- the recipient details look correct
- the amount is correct
- the network fee looks reasonable for on-chain sends

If the QR did not include an amount, enter the amount you want to pay.

## Confirm the payment

Tap **Next**, review the final confirmation screen, then complete the payment.

For on-chain Bitcoin payments, the transaction is broadcast to the Bitcoin network and may stay **Pending** until confirmed.

For Lightning payments, the invoice either succeeds quickly or returns an error if it is expired or cannot be paid.

## Tips

- Double-check the network before sending. A Lightning wallet cannot pay a regular on-chain address, and a Bitcoin wallet cannot pay a Lightning invoice.
- If the QR came from an image or screenshot, make sure it is current and not expired.
- Be careful with copied or forwarded QR codes from unknown sources.
