# ZISDMMASTERINST
**Description:** Master Installation of Master-sub relation
**Total Fields:** 3
**Key Fields:** MANDT, ANLAGE

## Programs Using This Table
- `zisdh0004`
- `zisdm0049`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `LARGE_ANLAGE` | CHAR | 1 |  | Large installation with many sub-installation |
