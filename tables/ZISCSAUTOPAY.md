# ZISCSAUTOPAY
**Description:** Autopay registration process
**Total Fields:** 6
**Key Fields:** MANDT, VKONT, GPART

## Programs Using This Table
- `ziscs0331`
- `ziscs0336`
- `ziscs0347`
- `ziscs0352`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `AUTOPAYIND` | CHAR | 1 |  | Autopay reminder |
| 5 | `AUTOPAYCALL` | CHAR | 20 |  | Autopay Reminder Call number |
| 6 | `AUTOPAYMAIL` | CHAR | 128 |  | e-mail Address of Contact Person at Business Partner |
