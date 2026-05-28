# ZCRM_BUT020
**Description:** For address data comparison use
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `ziscrmaddrcomp`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 2 | `ADDRNUMBER` | CHAR | 10 |  | Address Number |
| 3 | `XDFADR` | CHAR | 1 |  | Indicator: Address is standard address |
| 4 | `NATION` | CHAR | 1 |  | Version ID for International Addresses |
| 5 | `ADDRESS_GUID` | RAW | 16 |  | GUID of a Business Partner Address |
| 6 | `ADDR_VALID_FROM` | DEC | 15 |  | Validity Start of a Business Partner Address |
| 7 | `ADDR_VALID_TO` | DEC | 15 |  | Validity End of a Business Partner Address |
