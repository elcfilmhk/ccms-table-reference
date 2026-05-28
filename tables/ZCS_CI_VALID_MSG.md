# ZCS_CI_VALID_MSG
**Description:** Automated Change BP/Acct validation structure for BAPI
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_ci_validation_f========ft`
- `ziscs0318`
- `ziscs0320`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VSTELLE` | CHAR | 10 |  | Premise |
| 2 | `MSGTYP` | CHAR | 1 |  | Message Type |
| 3 | `MSGNR` | CHAR | 3 |  | Message number |
| 4 | `TEXT` | CHAR | 100 |  | Message Text |
