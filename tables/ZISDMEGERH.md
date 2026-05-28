# ZISDMEGERH
**Description:** Custome table for LPIS (Initial Device Number)
**Total Fields:** 18
**Key Fields:** MANDT, PID, EQUNR, SERNR, LOGIKNR, BIS

## Programs Using This Table
- `zisdm0059`
- `zisdm0060`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 3 | `EQUNR` | CHAR | 18 | 🔑 | Equipment Number |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `LOGIKNR` | NUMC | 18 | 🔑 | Logical device number |
| 6 | `BIS` | DATS | 8 | 🔑 | Date at Which a Time Slice Expires |
| 7 | `EINBDAT` | DATS | 8 |  | Installation date |
| 8 | `AUSBDAT` | DATS | 8 |  | Device removal date |
| 9 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 10 | `OBJNR` | CHAR | 18 |  | Object number (forecast) |
| 11 | `EQART` | CHAR | 10 |  | Type of Technical Object |
| 12 | `GROES` | CHAR | 32 |  | Size/dimensions |
| 13 | `INVNR` | CHAR | 25 |  | Inventory number |
| 14 | `TYPBZ` | CHAR | 20 |  | Manufacturer model number |
| 15 | `ZWGRUPPE` | CHAR | 8 |  | Register Group |
| 16 | `ATWRT` | CHAR | 30 |  | Characteristic Value |
| 17 | `DEVLOC` | CHAR | 30 |  | Device Location |
| 18 | `VSTELLE` | CHAR | 10 |  | Premise |
