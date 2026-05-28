# ZISCSFORMTEXT
**Description:** Table for message maintenance
**Total Fields:** 4
**Key Fields:** MANDT, TDFORM, MESSAGE_NO

## Programs Using This Table
- `zreprjt00`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TDFORM` | CHAR | 16 | 🔑 | Form Name |
| 3 | `MESSAGE_NO` | NUMC | 10 | 🔑 | Message number |
| 4 | `MESSAGE` | CHAR | 132 |  | The bill message |
