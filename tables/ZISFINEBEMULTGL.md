# ZISFINEBEMULTGL
**Description:** NEBE Charge Multiple GL table
**Total Fields:** 9
**Key Fields:** MANDT, HVORG, TVORG, VKONT, BUDAT, CPUDT, CPUTM, ZZSEQNO

## Programs Using This Table
- `z_fi_bapi_nebe_upload=========ft`
- `zisbi0132`
- `zisdm0369_ssr`
- `zisdm0369_ssr_mod`
- `zisfi0197`
- `zisfi0197_smis`
- `zisfi0210`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HVORG` | CHAR | 4 | 🔑 | Main Transaction for Line Item |
| 3 | `TVORG` | CHAR | 4 | 🔑 | Subtransaction for Document Item |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 6 | `CPUDT` | DATS | 8 | 🔑 | Date of entry |
| 7 | `CPUTM` | TIMS | 6 | 🔑 | Time of Entry |
| 8 | `ZZSEQNO` | NUMC | 4 | 🔑 | Sequence Num. |
| 9 | `DMBTR` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
