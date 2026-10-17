# Payment options for the 100 PHP invitation fee

Researched 2026-10-17. Fees per 100 PHP invitation.

| Option | Fee per invite | Confirmation | Notes |
|---|---|---|---|
| Manual QR (host scans your GCash/Maya/GoTyme QR) | ~0 PHP | You check each receipt/ref no. by hand | Fastest to launch; doesn't scale; personal wallets have monthly receive limits |
| PayMongo, QR Ph | 1.50 PHP (1.5%, VAT incl.) | Automatic (webhook) | GCash 2.5%, Maya 2.0%, cards 3.5% + 15 PHP. No setup or monthly fee |
| HitPay, QR Ph | ~1.00 PHP (1.0%, no fixed fee) | Automatic (API + webhooks) | Cheapest gateway found; next-day payout; rate from HitPay's own blog, verify on signup |
| Maya Business QR | 1.50 PHP (1.5%) | App/SMS alerts | No clear online API, so confirmation stays manual-ish |
| Xendit, QR Ph | ~15 PHP + VAT (1.5% + 11 PHP, min 15) | Automatic (webhook) | Flat 11 PHP per transaction makes it ~15% of a 100 PHP sale |

## Recommendation
Launch with manual QR, built so the host uploads a receipt and an admin approves it. Switch to PayMongo QR Ph (best-documented API, widely used; HitPay is ~0.50 PHP cheaper per invite and a fine alternative) (one QR that GCash, Maya, GoTyme and bank apps can all scan) once manual approval becomes a chore. Avoid Xendit at this price point.

Gateways need DTI or SEC registration plus a government ID.

Sources: [Wise QR Ph guide](https://wise.com/ph/blog/how-to-get-qr-ph), [HitPay vs PayMongo](https://hitpayapp.com/blog/hitpay-vs-paymongo-for-qr-ph-payments-2025-fee-payout-and-feature-showdown), [PayMongo fees](https://developers.paymongo.com/docs/fees-and-rates), [Xendit PH pricing](https://www.xendit.co/en-ph/pricing/)
