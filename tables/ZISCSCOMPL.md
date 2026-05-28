# ZISCSCOMPL
**Description:** Complaint information for service order
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `zreprjt00`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `HEADER` | RAW | 16 |  | Business Partner GUID |
| 3 | `PARNTER_NO` | CHAR | 32 |  | Case-Sensitive Element Name |
| 4 | `DATE_1` | NUMC | 15 |  | Time Stamp - Short Format |
| 5 | `OBJECT_ID` | CHAR | 10 |  | Transaction |
| 6 | `CODE` | CHAR | 4 |  | Code |
| 7 | `STAT` | CHAR | 5 |  | Object status |
