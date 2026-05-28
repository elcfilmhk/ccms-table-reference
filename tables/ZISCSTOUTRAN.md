# ZISCSTOUTRAN
**Description:** TOU drop-in drop-out document
**Total Fields:** 12
**Key Fields:** MANDT, VKONT, VERTRAG, ERDAT, ERTIM, ERNAM

## Programs Using This Table
- `ziscs0303`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 4 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `ERTIM` | TIMS | 6 | 🔑 | Created at |
| 6 | `ERNAM` | CHAR | 12 | 🔑 | Name of Person Who Created the Object |
| 7 | `ACTION` | CHAR | 1 |  | TOU Action |
| 8 | `TOU_PLAN` | CHAR | 10 |  | TOU Plan |
| 9 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 10 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 11 | `TOU_ERDAT` | DATS | 8 |  | TOU Created On |
| 12 | `TOU_ERNAM` | CHAR | 12 |  | TOU Created by |
