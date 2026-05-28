# ZISCSDEPOTMAP
**Description:** Location, Depot, Region Mapping
**Total Fields:** 6
**Key Fields:** CLIENT, REGIOAREA, DEPOT_ID, REGION

## Programs Using This Table
- `ziscs0026a`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | Client |
| 2 | `REGIOAREA` | CHAR | 8 | 🔑 | Regional structure area |
| 3 | `DEPOT_ID` | CHAR | 5 | 🔑 | Depot ID |
| 4 | `REGION` | CHAR | 10 | 🔑 | Region |
| 5 | `RADESCRIPT` | CHAR | 50 |  | Text Field |
| 6 | `DEPOT_NAME` | CHAR | 20 |  | Depot Name |
