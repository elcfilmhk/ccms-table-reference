# ZISDMLPBRDGCHG
**Description:** Meter reading change for Load Profile Billing
**Total Fields:** 14
**Key Fields:** MANDT, ABLBELNR

## Programs Using This Table
- `zisdm0208`
- `zisdm0236_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `ANLAGE` | CHAR | 10 |  | Installation |
| 4 | `GERNR` | CHAR | 18 |  | Device |
| 5 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 6 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 7 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 8 | `ORG_RDG` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 9 | `ORG_CONSUMPTION` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 10 | `REV_RDG` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 11 | `REV_CONSUMPTION` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 12 | `UPDATED_BY` | CHAR | 12 |  | User Name |
| 13 | `UPDATE_DATE` | DATS | 8 |  | Update date |
| 14 | `BILLTYPE` | CHAR | 1 |  | Bill Type |
