# ZISCSSMSBILL
**Description:** SMS billing registration process
**Total Fields:** 6
**Key Fields:** MANDT, VKONT, GPART

## Programs Using This Table
- `ziscs0158`
- `ziscs0160`
- `ziscs0320`
- `ziscs0336`
- `ziscs0346`
- `ziscs0352`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `SMSFAXIND` | CHAR | 1 |  | SMS/Fax billing indicator |
| 5 | `SMSPHONENO` | CHAR | 20 |  | SMS billing telephone number |
| 6 | `FAXPHONENO` | CHAR | 20 |  | Fax billing telephone number |
