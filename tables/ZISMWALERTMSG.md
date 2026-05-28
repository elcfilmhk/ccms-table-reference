# ZISMWALERTMSG
**Description:** Middleware Alert Message
**Total Fields:** 8
**Key Fields:** MANDT, PRGID

## Programs Using This Table
- `ziscrm0034`
- `ziscrm0035`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PRGID` | CHAR | 40 | 🔑 | Program ID |
| 3 | `SEVTY` | CHAR | 50 |  | Severity |
| 4 | `NAMEF` | CHAR | 50 |  | Name |
| 5 | `DESC1` | CHAR | 255 |  | Alert Description Line 1 |
| 6 | `DESC2` | CHAR | 255 |  | Alert Description Line 2 |
| 7 | `DESC3` | CHAR | 255 |  | Alert Description Line 3 |
| 8 | `CKNOW` | CHAR | 255 |  | Company Knowledge |
