# ZISFISDREV
**Description:** Initial security deposit reversal
**Total Fields:** 13
**Key Fields:** MANDT, VKONT, VERTRAG

## Programs Using This Table
- `zisfi0203`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 4 | `ORGINAL_AMT` | CURR | 11 |  | Original SD amount |
| 5 | `REVISED_AMT` | CURR | 11 |  | Revised SD amount |
| 6 | `REV_REASON` | CHAR | 4 |  | Reversal reason for security deposit |
| 7 | `RCAT` | CHAR | 10 |  | Rate category |
| 8 | `FLOOR_AREA` | DEC | 9 |  | Floor Area in Square Meters |
| 9 | `VOLTAGE` | CHAR | 10 |  | Voltage |
| 10 | `SECURITY` | CHAR | 12 |  | Security Deposit |
| 11 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `ERZET` | TIMS | 6 |  | Entry time |
| 13 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
