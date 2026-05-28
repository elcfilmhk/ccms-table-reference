# ZISCS_HSTR_ENTHD
**Description:** History table for custom table ZISCS_ENTL_HDR
**Total Fields:** 11
**Key Fields:** MANDT, VKONT, CPUDT, CPUTM, REFMTH, FIELDNAME

## Programs Using This Table
- `ziscs0226`
- `ziscs0226a`
- `ziscs0226b`
- `ziscs0226c`
- `ziscs0226d`
- `ziscs0226e`
- `ziscs0226f`
- `ziscs0226g`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CPUDT` | DATS | 8 | 🔑 | Date of entry |
| 4 | `CPUTM` | TIMS | 6 | 🔑 | Time of Entry |
| 5 | `REFMTH` | DATS | 8 | 🔑 | Entitlement ref month |
| 6 | `FIELDNAME` | CHAR | 30 | 🔑 | Field in respect of which change is recorded |
| 7 | `CDFLDVALO` | CHAR | 30 |  | Old contents of changed field |
| 8 | `CDFLDVALN` | CHAR | 30 |  | New contents of changed field |
| 9 | `ERNAM` | CHAR | 12 |  | Changed by |
| 10 | `XCPUDT` | DATS | 8 |  | Changed On |
| 11 | `XCPUTM` | TIMS | 6 |  | Time of Change |
