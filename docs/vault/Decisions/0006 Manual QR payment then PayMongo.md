# 0006 Manual QR payment, then PayMongo

- Date: 2026-10-17
- Decided by: Eric
- Decision: At launch, hosts pay 100 PHP by scanning Eric's GCash/Maya/GoTyme QR and uploading the receipt or reference number; an admin approves it before the invitation goes live. Later, add PayMongo QR Ph (1.5%) for automatic confirmation once DTI registration is done.
- Build note: keep payment behind a provider interface (manual | paymongo) so the gateway plugs in without reworking the flow.
- See [[Research/Payment options]].
