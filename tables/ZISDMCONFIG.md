# ZISDMCONFIG
**Description:** Table used to set up device management configuration
**Total Fields:** 5
**Key Fields:** MANDT, OBJ_NAME, FIELD, VLKEY

## Programs Using This Table
- `zisbi0168`
- `zisdm0035`
- `zisdm0050`
- `zisdm0072`
- `zisdm0181`
- `zisdm0182`
- `zisdm0189`
- `zisdm0192`
- `zisdm0198`
- `zisdm0199`
- `zisdm0202`
- `zisdm0210`
- `zisdm0221`
- `zisdm0223`
- `zisdm0226`
- `zisdm0227`
- `zisdm0228`
- `zisdm0232`
- `zisdm0238`
- `zisdm0262`
- `zisdm0264`
- `zised0012`
- `zismd0029`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 3 | `FIELD` | CHAR | 10 | 🔑 | List Box Field Name |
| 4 | `VLKEY` | CHAR | 4 | 🔑 | Value Key |
| 5 | `VLDES` | CHAR | 40 |  | Value Description |
