# ZISCSDEPOT
**Description:** Assign work centres to Depot
**Total Fields:** 7
**Key Fields:** MANDT, DEPOT_NAME, DEPOT_ID, ARBPL

## Programs Using This Table
- `z_bapi_isusmorder_exch========ft`
- `z_bapi_val_wr1_appt===========ft`
- `zisbi0013`
- `zisbi0016`
- `zisbi0105`
- `ziscs0002`
- `ziscs0007`
- `ziscs0007_gprs`
- `ziscs0012`
- `ziscs0014`
- `ziscs0014_adj`
- `ziscs0016`
- `ziscs0018`
- `ziscs0021`
- `ziscs0026`
- `ziscs0026a`
- `ziscs0027`
- `ziscs0039`
- `ziscs0046`
- `ziscs0049`
- `ziscs0060`
- `ziscs0074`
- `ziscs0108`
- `ziscs0110`
- `ziscs0115`
- `ziscs0133`
- `ziscs0142`
- `ziscs0157`
- `ziscs0287`
- `ziscs0363`
- `ziscs0364`
- `ziscs0465`
- `zisdm0019`
- `zisdm0021`
- `zisdm0023`
- `zisdm0024`
- `zisdm0036`
- `zisdm0058`
- `zisdm0080`
- `zisdm0087`
- `zisdm0089`
- `zisdm0119`
- `zisdm0130`
- `zisdm0139`
- `zisdm0169`
- `zisdm0190`
- `zisdm0215`
- `zisdm0348`
- `zisdm0420`
- `zisfi0030`
- `zisfi0031`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DEPOT_NAME` | CHAR | 20 | 🔑 | Depot Name |
| 3 | `DEPOT_ID` | CHAR | 5 | 🔑 | Depot ID |
| 4 | `ARBPL` | CHAR | 8 | 🔑 | Work Center |
| 5 | `ARBPL_CONV` | CHAR | 5 |  | Work centre conversion |
| 6 | `REGION` | CHAR | 10 |  | Region |
| 7 | `TEL_NR` | CHAR | 30 |  | First telephone no.: dialling code+number |
