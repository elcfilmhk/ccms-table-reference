# ZISCSBAPI2_IMPSTR
**Description:** Input Structure for Eservice Contact
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0004`
- `ziscs0336`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `CHANNEL` | CHAR | 1 |  | Dispatch |
| 3 | `ITEM` | CHAR | 10 |  | Item Number for Contact Number |
| 4 | `SMS` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 5 | `STANDARD` | CHAR | 1 |  | Standard |
| 6 | `DELETE` | CHAR | 1 |  | Deletion Flag |
| 7 | `STATUS` | CHAR | 1 |  | Status |
