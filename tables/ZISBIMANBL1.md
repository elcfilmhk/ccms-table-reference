# ZISBIMANBL1
**Description:** Manual bill  configuration 1
**Total Fields:** 8
**Key Fields:** MANDT, TARIFTYP, FL_COL, BELZART

## Programs Using This Table
- `zisbi0027`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 3 | `FL_COL` | NUMC | 2 | 🔑 | Number of Columns |
| 4 | `BELZART` | CHAR | 6 | 🔑 | Line Item Type |
| 5 | `POS` | INT2 | 5 |  | Position |
| 6 | `WIDTH` | INT1 | 3 |  | Width |
| 7 | `DESCRIPT` | CHAR | 20 |  | Description |
| 8 | `ACTIVE` | CHAR | 1 |  | Active |
