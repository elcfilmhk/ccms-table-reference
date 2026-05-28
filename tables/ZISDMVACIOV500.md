# ZISDMVACIOV500
**Description:** vacant installation with consumption after move-out over 500
**Total Fields:** 14
**Key Fields:** MANDT, ANLAGE, AUSZBELEG

## Programs Using This Table
- `ziscs0283`
- `ziscs0283a`
- `zisdm0190`
- `zisdm0215`
- `zisdm0232`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `AUSZBELEG` | CHAR | 12 | 🔑 | Consecutive number of move-out document |
| 4 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 5 | `VSTELLE` | CHAR | 10 |  | Premise |
| 6 | `CONSUMPTION` | DEC | 16 |  | Entry value (installed value) for a device |
| 7 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 8 | `DM_ORDER_NO` | CHAR | 12 |  | DM Order Number |
| 9 | `IDAT2` | DATS | 8 |  | Technical completion date |
| 10 | `MR_ORDER_NO` | CHAR | 12 |  | MR Order Number |
| 11 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 12 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 13 | `STATUS` | CHAR | 1 |  | Single-Character Flag |
| 14 | `NO_GEN_INDC` | CHAR | 1 |  | The indicator to indicate no generation of letter |
