# ZISCSSER_CONTACT
**Description:** Eservice Contact
**Total Fields:** 16
**Key Fields:** MANDT, VKONT, DISPATCH, ITEM

## Programs Using This Table
- `z_bapi_search_contact=========ft`
- `zisbi0084`
- `ziscs0004`
- `ziscs0134`
- `ziscs0178`
- `ziscs0324`
- `ziscs0333`
- `ziscs0334`
- `ziscs0336`
- `ziscs0338`
- `ziscs0346`
- `ziscs0347`
- `ziscs0348`
- `ziscs0350`
- `ziscs0352`
- `ziscs0372`
- `ziscs0376`
- `ziscs0484`
- `ziscs1118`
- `zisfi0102`
- `zisfi0110`
- `zisfi0254`
- `zrca_ssr_cust_extract`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `DISPATCH` | CHAR | 1 | 🔑 | Dispatch |
| 4 | `ITEM` | CHAR | 10 | 🔑 | Item Number for Contact Number |
| 5 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 6 | `STANDARD` | CHAR | 1 |  | Standard |
| 7 | `ATTRIBUTE1` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 8 | `ATTRIBUTE2` | CHAR | 50 |  | Attribute 2 for Contact Information |
| 9 | `ATTRIBUTE3` | CHAR | 50 |  | Attribute 3 for Contact Information |
| 10 | `ATTRIBUTE4` | CHAR | 50 |  | Attribute 4 for Contact Information |
| 11 | `ATTRIBUTE5` | CHAR | 50 |  | Attribute 5 for Contact Information |
| 12 | `STATUS` | CHAR | 1 |  | Status |
| 13 | `ERDAT` | CHAR | 14 |  | Creation Date |
| 14 | `ERNAM` | CHAR | 12 |  | Create By |
| 15 | `AEDAT` | CHAR | 14 |  | Change Date |
| 16 | `AENAM` | CHAR | 12 |  | Change By |
