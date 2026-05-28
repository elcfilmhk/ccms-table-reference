# ZBACBLFLD
**Description:** List display column attributes
**Total Fields:** 14
**Key Fields:** MANDT, PROGRAMM, LISTVARI, FIELDNAME

## Programs Using This Table
- `zbacbe020`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROGRAMM` | CHAR | 40 | 🔑 | ABAP Program Name |
| 3 | `LISTVARI` | CHAR | 15 | 🔑 | List variant |
| 4 | `FIELDNAME` | CHAR | 30 | 🔑 | Field Name |
| 5 | `ACTIVE` | CHAR | 1 |  | Element is active |
| 6 | `FIELDPOS` | NUMC | 2 |  | Verification: Column position |
| 7 | `LENGTH` | NUMC | 4 |  | Visible column width |
| 8 | `COLOR` | NUMC | 1 |  | Text Color |
| 9 | `INTENSIFIED` | CHAR | 1 |  | The field is displayed as highlighted |
| 10 | `HOTSPOT` | CHAR | 1 |  | Hotspot |
| 11 | `HEADER` | CHAR | 40 |  | Header text |
| 12 | `FUNCTION` | CHAR | 30 |  | Name of Function Module |
| 13 | `SORT` | CHAR | 10 |  | Sort criteria |
| 14 | `DATA` | CHAR | 10 |  | Data select criteria |
