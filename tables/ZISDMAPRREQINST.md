# ZISDMAPRREQINST
**Description:** Store the approval metering reading installation data
**Total Fields:** 5
**Key Fields:** MANDT, ABLBELNR, ANLAGE, ABLESGR

## Programs Using This Table
- `zisdm0181`
- `zisdm0182`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `ABLESGR` | CHAR | 2 | 🔑 | Meter reading reason |
| 5 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
