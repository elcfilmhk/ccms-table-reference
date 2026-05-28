# ZISCSEEC_AGENDA
**Description:** General Configuration Table for EE&C
**Total Fields:** 8
**Key Fields:** MANDT, OBJ_NAME, TYPE, COUNTER

## Programs Using This Table
- `zisbi0268`
- `ziscrm0316`
- `ziscrm0318`
- `ziscs0386_eec`
- `ziscs0387_eec`
- `ziscs0389_eec`
- `ziscs0390_eec`
- `ziscs0393_eec`
- `ziscs0518`
- `ziscs0533`
- `ziscs0534`
- `ziscs0734`
- `ziscs0841`
- `ziscs1121`
- `ziscs1131`
- `ziscs1133`
- `ziscs1138`
- `ziscs1141`
- `ziscs_cron_zcs_ca_antispam`
- `ziscs_sms02`
- `ziscseec_eml_postman_bcs`
- `ziscseec_eml_postman_radica`
- `zisdm0022`
- `zisfi0250`
- `zisfi0250_backup`
- `zisfi0250_backup_1`
- `zprintdoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 3 | `TYPE` | CHAR | 30 | 🔑 | ABAP: Name of Variant Variable |
| 4 | `COUNTER` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 5 | `SIGN` | CHAR | 1 |  | ABAP: ID: I/E (include/exclude values) |
| 6 | `OPTI` | CHAR | 2 |  | ABAP: Selection option (EQ/BT/CP/...) |
| 7 | `LOW` | CHAR | 255 |  | Case-sensitive Text of 255 length |
| 8 | `HIGH` | CHAR | 255 |  | Case-sensitive Text of 255 length |
