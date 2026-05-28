# ZISDM_DRRETRYCA
**Description:** Autogrid retry(Multiple CA's Exception report)
**Total Fields:** 5
**Key Fields:** MANDT, TARGET_CA, RELATED_CA, AEDAT, TIME

## Programs Using This Table
- `zcl_object_move`
- `zisdm0364`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARGET_CA` | CHAR | 12 | 🔑 | Target CA Account |
| 3 | `RELATED_CA` | CHAR | 12 | 🔑 | Related CA Account |
| 4 | `AEDAT` | DATS | 8 | 🔑 | Updated Date |
| 5 | `TIME` | TIMS | 6 | 🔑 | Updated Time |
