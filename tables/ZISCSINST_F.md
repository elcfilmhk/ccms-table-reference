# ZISCSINST_F
**Description:** Custom table for ICS01  - Meter Level
**Total Fields:** 8
**Key Fields:** MANDT, VSTELLE, GERNR

## Programs Using This Table
- `ziscs0368`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `GERNR` | CHAR | 8 | 🔑 | Character field, 8 characters long |
| 4 | `INSDATE` | CHAR | 10 |  | Character Field Length = 10 |
| 5 | `FUNKLAS` | CHAR | 4 |  | Not More Closely Defined Area, Possibly Used for Patchlevels |
| 6 | `GERWECHS` | CHAR | 2 |  | Version Number Component |
| 7 | `ZZLAT` | CHAR | 15 |  | Latitude |
| 8 | `ZZLONG` | CHAR | 15 |  | Longitude |
