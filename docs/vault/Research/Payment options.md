# Payment options for the 100 PHP invitation fee

Researched 2026-10-17. Fees per 100 PHP invitation.

| Option | Fee per invite | Confirmation | Notes |
|---|---|---|---|
| Manual QR (host scans your GCash/Maya/GoTyme QR) | ~0 PHP | You check each receipt/ref no. by hand | Fastest to launch; doesn't scale; personal wallets have monthly receive limits |
| PayMongo, QR Ph | 1.50 PHP (1.5%, VAT incl.) | Automatic (webhook) | GCash 2.5%, Maya 2.0%, cards 3.5% + 15 PHP. No setup or monthly fee |
| Xendit, QR Ph | ~15 PHP + VAT (1.5% + 11 PHP, min 15) | Automatic (webhook) | Flat 11 PHP per transaction makes it ~15% of a 100 PHP sale |

## Recommendation
Launch with manual QR, built so the host uploads a receipt and an admin approves it. Switch to PayMongo QR Ph (one QR that GCash, Maya, GoTyme and bank apps can all scan) once manual approval becomes a chore. Avoid Xendit at this price point.

Sources: [PayMongo fees](https://developers.paymongo.com/docs/fees-and-rates), [Xendit PH pricing](https://www.xendit.co/en-ph/pricing/)
