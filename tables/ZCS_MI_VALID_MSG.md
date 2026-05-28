# ZCS_MI_VALID_MSG
**Description:** Automated Move-in validation structure for BAPI
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_mi_validation==========ft`
- `ziscs0256`
- `ziscs0257`
- `ziscs0297`
- `ziscs0299`
- `ziscs0315`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VSTELLE` | CHAR | 10 |  | Premise |
| 2 | `MSGTYP` | CHAR | 1 |  | Message Type |
| 3 | `MSGNR` | CHAR | 3 |  | Message number |
| 4 | `TEXT` | CHAR | 100 |  | Message Text |
