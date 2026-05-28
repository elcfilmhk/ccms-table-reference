# ZISDMPODLOG0
**Description:** Automatic creation of POD Logging Table 0
**Total Fields:** 8
**Key Fields:** MANDT, REF_NO, ANLAGE

## Programs Using This Table
- `zisdm0127`
- `zised0005`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REF_NO` | NUMC | 9 | 🔑 | Reference Number |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `SERNR` | CHAR | 18 |  | Serial Number |
| 5 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 6 | `ACTVDATE` | DATS | 8 |  | Activity date |
| 7 | `ACTNDATE` | DATS | 8 |  | Action date |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
