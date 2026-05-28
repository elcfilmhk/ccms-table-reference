# ZISDMMTRUG
**Description:** Meter Model to Download Sequence and Instruction Codes
**Total Fields:** 9
**Key Fields:** MANDT, OBJECTTYPE, REGNUMBER

## Programs Using This Table
- `zisdh0002`
- `zisdm0027`
- `zisdm0050`
- `zisdm0051`
- `zisdm0082`
- `zisdm0409`
- `zismd0008`
- `zismd0011`
- `zismd0030`
- `zrdm_dr_rep`
- `zrdm_us_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJECTTYPE` | CHAR | 10 | 🔑 | Type of Technical Object |
| 3 | `REGNUMBER` | NUMC | 3 | 🔑 | Register |
| 4 | `CISSREG` | CHAR | 2 |  | CISS Reference Register Number |
| 5 | `DWNLSEQ` | NUMC | 2 |  | Register download sequence |
| 6 | `INSTRCODE1` | CHAR | 2 |  | Instruction Code |
| 7 | `INSTRCODE2` | CHAR | 2 |  | Instruction Code |
| 8 | `INSTRCODE3` | CHAR | 2 |  | Instruction Code |
| 9 | `REG_CODE` | CHAR | 15 |  | Code for Identifying a Register |
