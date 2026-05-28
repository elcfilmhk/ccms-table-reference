# ZCREATECA_MSG
**Description:** Automated Move-in validation message
**Total Fields:** 6
**Key Fields:** MANDT, TXNNUM, VSTELLE, MSGTYP, MSGNR

## Programs Using This Table
- `ziscs0256`
- `ziscs0257`
- `ziscs0259`
- `ziscs0261`
- `ziscs0270`
- `ziscs0297`
- `ziscs0299`
- `ziscs0309`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TXNNUM` | CHAR | 10 | 🔑 | CRM transaction no. |
| 3 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 4 | `MSGTYP` | CHAR | 1 | 🔑 | Message Type |
| 5 | `MSGNR` | CHAR | 3 | 🔑 | Message number |
| 6 | `TEXT` | CHAR | 100 |  | Message Text |
