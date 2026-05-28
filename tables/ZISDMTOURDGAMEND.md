# ZISDMTOURDGAMEND
**Description:** Store TOU reading waiting for amendment
**Total Fields:** 14
**Key Fields:** MANDT, ABLBELNR

## Programs Using This Table
- `zisdm0236`
- `zisdm0236_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `VERTRAG` | CHAR | 10 |  | Contract |
| 4 | `ANLAGE` | CHAR | 10 |  | Installation |
| 5 | `GERNR` | CHAR | 18 |  | Device |
| 6 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 7 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 8 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 9 | `ATIM` | CHAR | 4 |  | Meter reading time (relevant to billing) |
| 10 | `READING` | DEC | 31 |  | Meter Reading |
| 11 | `RELEASE_BILL_BLK` | CHAR | 1 |  | Release Billing Block indicator |
| 12 | `PID` | NUMC | 5 |  | Process ID |
| 13 | `PROCESSED` | CHAR | 1 |  | Character Field Length 1 |
| 14 | `ERROR_MSG` | CHAR | 100 |  | Character 100 |
