# ZISBWREFUND
**Description:** Refund Type and Channel
**Total Fields:** 5
**Key Fields:** MANDT, DOC1R

## Programs Using This Table
- `zisfi0028`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DOC1R` | CHAR | 24 | 🔑 | Reference to Payment Document |
| 3 | `LAUFD` | DATS | 8 |  | Date ID |
| 4 | `ZZRFTYPE` | CHAR | 1 |  | Refund Type (1=Auto, 2=non auto) |
| 5 | `ZZRFCHANNEL` | CHAR | 6 |  | Refund Channel |
