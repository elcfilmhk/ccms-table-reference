# ZISCSPROMALERT
**Description:** Promotion alert
**Total Fields:** 6
**Key Fields:** MANDT, PROMONAME, VKONT, PROMOUSER, PROMALERTDATE, PROMALERTTIME

## Programs Using This Table
- `ziscs0164`
- `zpromotion`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROMONAME` | CHAR | 10 | 🔑 | Promotion activity name |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `PROMOUSER` | CHAR | 12 | 🔑 | Responsible person user ID |
| 5 | `PROMALERTDATE` | DATS | 8 | 🔑 | Promotion alert date |
| 6 | `PROMALERTTIME` | TIMS | 6 | 🔑 | Promotion alert time |
