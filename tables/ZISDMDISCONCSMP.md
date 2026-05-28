# ZISDMDISCONCSMP
**Description:** Disconnected installation with consumption
**Total Fields:** 37
**Key Fields:** MANDT, DEPOT, RPTCAT, VSTELLE, DISCNO

## Programs Using This Table
- `zisdm0087`
- `zisdm0169`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DEPOT` | CHAR | 20 | 🔑 | Depot Name |
| 3 | `RPTCAT` | CHAR | 1 | 🔑 | Report Category |
| 4 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 5 | `DISCNO` | CHAR | 12 | 🔑 | Disconnection document number |
| 6 | `RPTYPE` | CHAR | 1 |  | Report Type |
| 7 | `LOGIKNR` | NUMC | 18 |  | Logical device number |
| 8 | `DISCSTATE` | CHAR | 2 |  | Disconnection status |
| 9 | `AB` | DATS | 8 |  | Date from which a disconnection is valid |
| 10 | `ACTAB` | DATS | 8 |  | Actual Disconnection Date |
| 11 | `ANLAGE` | CHAR | 10 |  | Installation |
| 12 | `DEVLOC` | CHAR | 30 |  | Device Location |
| 13 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 14 | `GERNR` | CHAR | 18 |  | Serial Number |
| 15 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 16 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 17 | `VERTRAG` | CHAR | 10 |  | Contract |
| 18 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 19 | `EINBDAT` | DATS | 8 |  | Installation date |
| 20 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 21 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 22 | `LTMRD` | DATS | 8 |  | Latest Meter Reading Date |
| 23 | `LTMRR` | CHAR | 2 |  | Latest Meter Reading Reason |
| 24 | `LTRDG` | CHAR | 31 |  | Latest meter reading |
| 25 | `PVMRD` | DATS | 8 |  | Previous Meter Reading Date |
| 26 | `PVMRR` | CHAR | 2 |  | Previous Meter Reading Reason |
| 27 | `PVRDG` | CHAR | 31 |  | Previous mete reading just before the latest mete reading |
| 28 | `CSMP_RDG` | DEC | 31 |  | Billing quantity for internal billing format |
| 29 | `DISC_RDG` | CHAR | 31 |  | Disconnection meter reading |
| 30 | `LAST_MO_RDG` | CHAR | 31 |  | Last move-out meter reading |
| 31 | `CURR_MI_RDG` | CHAR | 31 |  | Current move-in reading |
| 32 | `ADDR` | CHAR | 80 |  | Address of Disconnected Installation |
| 33 | `VBSART` | CHAR | 8 |  | Type of premise |
| 34 | `REGION_GROUP` | CHAR | 8 |  | Regional structure grouping |
| 35 | `AUFNR` | CHAR | 12 |  | Order Number |
| 36 | `ILART` | CHAR | 3 |  | Maintenance activity type |
| 37 | `QMNUM` | CHAR | 12 |  | Notification No |
