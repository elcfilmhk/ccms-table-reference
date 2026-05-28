# ZISBINEBEMSG
**Description:** NEBE Bill Generation Request Message Table
**Total Fields:** 21
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `ziscrm0010`
- `ziscrm0031`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | NEBE document number |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `CHARGE_TYPE` | CHAR | 3 |  | Charge type |
| 5 | `REF_NO` | CHAR | 20 |  | Reference no. |
| 6 | `LINE_NO` | NUMC | 2 |  | Total no. of message line |
| 7 | `MSG1` | CHAR | 120 |  | Message line 1 |
| 8 | `MSG2` | CHAR | 120 |  | Message line 2 |
| 9 | `MSG3` | CHAR | 120 |  | Message line 3 |
| 10 | `MSG4` | CHAR | 120 |  | Message line 4 |
| 11 | `MSG5` | CHAR | 120 |  | Message line 5 |
| 12 | `MSG6` | CHAR | 120 |  | Message line 6 |
| 13 | `MSG7` | CHAR | 120 |  | Message line 7 |
| 14 | `MSG8` | CHAR | 120 |  | Message line 8 |
| 15 | `MSG9` | CHAR | 120 |  | Message line 9 |
| 16 | `MSG10` | CHAR | 120 |  | Message line 10 |
| 17 | `MSG11` | CHAR | 120 |  | Message line 11 |
| 18 | `MSG12` | CHAR | 120 |  | Message line 12 |
| 19 | `MSG13` | CHAR | 120 |  | Message line 13 |
| 20 | `MSG14` | CHAR | 120 |  | Message line 14 |
| 21 | `MSG15` | CHAR | 120 |  | Message line 15 |
