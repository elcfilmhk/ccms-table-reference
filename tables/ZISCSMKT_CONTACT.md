# ZISCSMKT_CONTACT
**Description:** eMarketing Contact
**Total Fields:** 16
**Key Fields:** MANDT, VKONT, DISPATCH, ITEM

## Programs Using This Table
- `ziscs0099`
- `ziscs0351`
- `ziscs0458`
- `ziscs0459`
- `ziscs0463`
- `ziscs1118`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `DISPATCH` | CHAR | 1 | 🔑 | Dispatch Method for e-Marketing |
| 4 | `ITEM` | CHAR | 10 | 🔑 | Item Number for Contact Number |
| 5 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 6 | `STANDARD` | CHAR | 1 |  | Standard |
| 7 | `ATTRIBUTE1` | CHAR | 255 |  | Attribute 1 for Contact Information |
| 8 | `ATTRIBUTE2` | CHAR | 50 |  | Attribute 2 for Contact Information |
| 9 | `ATTRIBUTE3` | CHAR | 50 |  | Attribute 3 for Contact Information |
| 10 | `ATTRIBUTE4` | CHAR | 50 |  | Attribute 4 for Contact Information |
| 11 | `ATTRIBUTE5` | CHAR | 50 |  | Attribute 5 for Contact Information |
| 12 | `STATUS` | CHAR | 1 |  | Status |
| 13 | `ERDAT` | CHAR | 14 |  | Creation Date |
| 14 | `ERNAM` | CHAR | 12 |  | Create By |
| 15 | `AEDAT` | CHAR | 14 |  | Change Date |
| 16 | `AENAM` | CHAR | 12 |  | Change By |
