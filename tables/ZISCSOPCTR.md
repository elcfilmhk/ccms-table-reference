# ZISCSOPCTR
**Description:** Mapping of Operation Center
**Total Fields:** 4
**Key Fields:** MANDT, OPERATION_CTR

## Programs Using This Table
- `ziscs0111`
- `ziscs0118`
- `ziscs0119`
- `ziscs0460`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPERATION_CTR` | CHAR | 2 | 🔑 | Operation Center |
| 3 | `DESCRIPTION` | CHAR | 20 |  | Operation Center Full Name |
| 4 | `REGION` | CHAR | 20 |  | Region for operation center |
