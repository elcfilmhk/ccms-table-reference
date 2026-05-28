# ZISDMNEWSRVTOL
**Description:** Tolerance limit for meter not installed for follow-up action
**Total Fields:** 4
**Key Fields:** MANDT, PARM_TYPE

## Programs Using This Table
- `zisdm0254`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PARM_TYPE` | CHAR | 1 | 🔑 | The parameter type D=Deafult |
| 3 | `DAYSFORWARNING` | NUMC | 2 |  | Days after meter not installed which trigger warning |
| 4 | `DAYSFORCLOSING` | NUMC | 2 |  | Days after meter not installed will have case closed |
