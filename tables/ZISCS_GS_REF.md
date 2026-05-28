# ZISCS_GS_REF
**Description:** Government Subsidy Reference
**Total Fields:** 18
**Key Fields:** MANDT, NUM_GS, SCHEME, SEQ

## Programs Using This Table
- `ziscs0226f`
- `ziscs0226g`
- `ziscs0243`
- `ziscs0244`
- `ziscs0859`
- `ziscs0860_new`
- `ziscs0861`
- `zisfi0185`
- `zisfi0349`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `NUM_GS` | NUMC | 3 | 🔑 | Gov Subsidy No. |
| 3 | `SCHEME` | CHAR | 10 | 🔑 | Scheme of Gov Subsidy |
| 4 | `SEQ` | NUMC | 3 | 🔑 | Seq No. |
| 5 | `SCHEME_EN` | CHAR | 50 |  | Government Subsidy Scheme English Description |
| 6 | `SCHEME_ZF` | CHAR | 50 |  | Government Subsidy Scheme Chinese Description |
| 7 | `BEGDT` | DATS | 8 |  | From date |
| 8 | `ENDDT` | DATS | 8 |  | To date |
| 9 | `OFSET` | INT1 | 3 |  | Offset |
| 10 | `LEN` | INT1 | 3 |  | Length |
| 11 | `VAL` | CHAR | 8 |  | Value |
| 12 | `GS_ENTL` | INT1 | 3 |  | No. of Gov Subsidy Entitlement |
| 13 | `DDTEXT` | CHAR | 30 |  | Subsidy key |
| 14 | `VALIDTO` | DATS | 8 |  | Subsidy end date |
| 15 | `EXPIRY` | DATS | 8 |  | Expiry Date |
| 16 | `GS_SETSEQ` | NUMC | 3 |  | Gov Subsidy Settle Sequence |
| 17 | `GRACEPERIOD_END` | DATS | 8 |  | Grace Period End Date |
| 18 | `SCHEME_CAT` | CHAR | 10 |  | Scheme of Gov Subsidy |
