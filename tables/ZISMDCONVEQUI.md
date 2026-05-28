# ZISMDCONVEQUI
**Description:** Meter Output Interface File Records from Parallel Processes
**Total Fields:** 37
**Key Fields:** MANDT, METERID

## Programs Using This Table
- `zismd0005`
- `zismd0006`
- `zismd0010`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `METERID` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `METERNUMBER` | CHAR | 18 |  | Serial Number |
| 4 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 5 | `ANLAGE` | CHAR | 10 |  | Installation |
| 6 | `STATUS` | CHAR | 30 |  | Object status |
| 7 | `MULTIPLIER` | CHAR | 10 |  | Multiplier |
| 8 | `TYPBZ` | CHAR | 20 |  | Manufacturer model number |
| 9 | `DST_OPTION` | CHAR | 16 |  | DST Option |
| 10 | `HERST` | CHAR | 30 |  | Manufacturer of asset |
| 11 | `PHASE_CODE` | CHAR | 16 |  | Phase of the meter |
| 12 | `STORTZUS` | CHAR | 30 |  | Addition to device location |
| 13 | `DATE_INIT` | DATS | 8 |  | Last test date of the meter |
| 14 | `EINBDAT` | DATS | 8 |  | Installation date |
| 15 | `PT_RATIO` | CHAR | 10 |  | PT Ratio |
| 16 | `CT_RATIO` | CHAR | 10 |  | CT Ratio |
| 17 | `EFF_START_DATE` | DATS | 8 |  | Construction date of the device |
| 18 | `GROES` | CHAR | 18 |  | Size/dimension |
| 19 | `CONTACT_FORM` | CHAR | 1 |  | Contact Form - Three Wires -  'C' |
| 20 | `METER_CONFIG` | CHAR | 1 |  | Meter Config |
| 21 | `ZWGRUPPE` | CHAR | 8 |  | Register Group |
| 22 | `FUNKLAS` | CHAR | 8 |  | Function class |
| 23 | `BAUKLAS` | CHAR | 8 |  | Construction class |
| 24 | `MATNR` | CHAR | 18 |  | Material Number |
| 25 | `BGLJAHR` | NUMC | 4 |  | Certification Year |
| 26 | `EQART` | CHAR | 10 |  | Type of Technical Object |
| 27 | `USER_STATUS` | CHAR | 30 |  | Object status |
| 28 | `ACC_FULL_LO_PF1` | CHAR | 30 |  | Characteristic Value |
| 29 | `ACC_LIGHT_LO_PF1` | CHAR | 30 |  | Characteristic Value |
| 30 | `ACC_INDLOAD_PF05` | CHAR | 30 |  | Characteristic Value |
| 31 | `REPROG_RATE_ID` | CHAR | 8 |  | Reprogram rate ID |
| 32 | `LAST_REPROG_DATE` | DATS | 8 |  | Last Reprogram date |
| 33 | `INVNR` | CHAR | 25 |  | Inventory number |
| 34 | `EQKTX` | CHAR | 40 |  | Description of Technical Object |
| 35 | `APPROVALNR` | CHAR | 15 |  | Device inspection number |
| 36 | `METER_RDG_METHOD` | CHAR | 30 |  | Characteristic value description |
| 37 | `TASK_OPERATION` | CHAR | 10 |  | Task Operation |
