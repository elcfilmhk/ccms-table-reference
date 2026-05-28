# ZMIERROR
**Description:** Move-in Automation validation message
**Total Fields:** 4
**Key Fields:** MANDT, MSGNR

## Programs Using This Table
- `ziscs0256`
- `ziscs0297`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MSGNR` | CHAR | 3 | 🔑 | Message number |
| 3 | `USER_FLG` | CHAR | 1 |  | Show in Task Mngr |
| 4 | `TEXT` | CHAR | 100 |  | Message Text |
