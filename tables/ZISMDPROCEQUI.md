# ZISMDPROCEQUI
**Description:** Meter serial number for meter information migration
**Total Fields:** 4
**Key Fields:** MANDT, REPID, PID, SERNR

## Programs Using This Table
- `zismd0005`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 3 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
