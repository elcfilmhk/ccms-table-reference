# ZISDMNEWSRVCASE
**Description:** New service case for follow-up
**Total Fields:** 12
**Key Fields:** MANDT, ID

## Programs Using This Table
- `zisdm0050`
- `zisdm0254`
- `zrdm_us_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ID` | NUMC | 10 | 🔑 | ID for new service case |
| 3 | `ROUTE_ID` | CHAR | 8 |  | Route ID of the route the new service meter is reported |
| 4 | `GERNR` | CHAR | 18 |  | Device |
| 5 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 6 | `ADATTATS` | DATS | 8 |  | Actual meter reading date |
| 7 | `ATIMTATS` | CHAR | 4 |  | Actual meter reading time |
| 8 | `NEARESTMETER` | CHAR | 18 |  | Device |
| 9 | `METERREADERID` | CHAR | 8 |  | The meter reader id |
| 10 | `ANLAGE` | CHAR | 10 |  | Installation |
| 11 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 12 | `STATUS` | CHAR | 1 |  | The status of the new service case |
