# ZISMDPROCINST
**Description:** Relationship between job ID and installation
**Total Fields:** 5
**Key Fields:** MANDT, REPID, PID, ANLAGE, VSTELLE

## Programs Using This Table
- `zismd0001`
- `zismd0002`
- `zismd0007`
- `zismd0009`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client ID |
| 2 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 3 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 4 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 5 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
