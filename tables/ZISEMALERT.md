# ZISEMALERT
**Description:** Energy Manager - Alert condition for PEM
**Total Fields:** 18
**Key Fields:** MANDT, CAMETER, RULENO, OPERAND

## Programs Using This Table
- `zisem_energy_monitor`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CAMETER` | CHAR | 18 | 🔑 | Energy Manager - Number of CA or Meter |
| 3 | `RULENO` | CHAR | 10 | 🔑 | Energy Manager - Rule Number |
| 4 | `OPERAND` | CHAR | 1 | 🔑 | Energy Management - Operand type |
| 5 | `OPERATOR01` | CHAR | 1 |  | Energy Management - Operator |
| 6 | `VALUE_TYPE01` | CHAR | 1 |  | Energy Management - Value type |
| 7 | `VALUE01` | DEC | 16 |  | Profile value |
| 8 | `RELATION` | CHAR | 1 |  | Energy Management - Relation |
| 9 | `OPERATOR02` | CHAR | 1 |  | Energy Management - Operator |
| 10 | `VALUE_TYPE02` | CHAR | 1 |  | Energy Management - Value type |
| 11 | `VALUE02` | DEC | 16 |  | Profile value |
| 12 | `CAFLAG` | CHAR | 1 |  | Flag to select Contract Accounts |
| 13 | `VERTRAG` | CHAR | 10 |  | Contract |
| 14 | `USERID_CR` | CHAR | 50 |  | Energy Manager - ID of CLP Web user |
| 15 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 16 | `ERTIM` | TIMS | 6 |  | Entry time |
| 17 | `USERID_CH` | CHAR | 50 |  | Energy Manager - ID of CLP Web user |
| 18 | `AEDAT` | DATS | 8 |  | Date of Last Change |
