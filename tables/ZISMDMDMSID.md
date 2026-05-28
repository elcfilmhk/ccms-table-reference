# ZISMDMDMSID
**Description:** MDMS mapping between SAP system ID and MDMS server name
**Total Fields:** 3
**Key Fields:** MANDT, SYSID

## Programs Using This Table
- `zismd0030`
- `zismd0032`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SYSID` | CHAR | 8 | 🔑 | Name of SAP System |
| 3 | `MDMS` | CHAR | 50 |  | MDMS server name |
