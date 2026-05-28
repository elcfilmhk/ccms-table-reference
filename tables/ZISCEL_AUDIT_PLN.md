# ZISCEL_AUDIT_PLN
**Description:** Audit plan
**Total Fields:** 8
**Key Fields:** MANDT, AUD_YEAR

## Programs Using This Table
- `ziscs0400`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUD_YEAR` | CHAR | 4 | 🔑 | Audit year |
| 3 | `ACNUM` | NUMC | 6 |  | No. of account |
| 4 | `CRE_DAT` | DATS | 8 |  | Create date |
| 5 | `CRE_TIM` | TIMS | 6 |  | Create time |
| 6 | `CRE_USR` | CHAR | 12 |  | Create user |
| 7 | `TCFLG` | CHAR | 1 |  | Target change allow flag |
| 8 | `REGEN` | CHAR | 1 |  | Target regenerate indicator |
