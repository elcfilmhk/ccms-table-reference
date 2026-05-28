# ZISCSUCCTEXT
**Description:** Tables and Fields to be checked
**Total Fields:** 8
**Key Fields:** MANDT, ZGROUP, TDOBJECT, TDID

## Programs Using This Table
- `ziscs0600`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZGROUP` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 3 | `TDOBJECT` | CHAR | 10 | 🔑 | Texts: application object |
| 4 | `TDID` | CHAR | 4 | 🔑 | Text ID |
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Structure of Selection Criteria Definition Control |
| 6 | `OPERAND` | CHAR | 2 |  | Operand |
| 7 | `LOW` | CHAR | 50 |  | Field Value |
| 8 | `HIGH` | CHAR | 50 |  | Field Value |
