# ZTERMINATECA_MSG
**Description:** Table of Move-out application error message through Fax and
**Total Fields:** 6
**Key Fields:** MANDT, TXNNUM, VSTELLE, MSGTYP, MSGNR

## Programs Using This Table
- `ziscs0298`
- `ziscs0315`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TXNNUM` | CHAR | 10 | 🔑 | CRM transaction no. |
| 3 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 4 | `MSGTYP` | CHAR | 1 | 🔑 | Message Type |
| 5 | `MSGNR` | CHAR | 3 | 🔑 | Message number |
| 6 | `TEXT` | CHAR | 100 |  | Message Text |
