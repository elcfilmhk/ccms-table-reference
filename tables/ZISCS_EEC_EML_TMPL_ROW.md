# ZISCS_EEC_EML_TMPL_ROW
**Description:** Input structure for FM ZISCSEEC_QUEUE_EMAIL
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `ziscseec_queue_email==========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `EML_TEMPL_OBJNAME` | CHAR | 40 |  | Object Name in Object Directory |
| 2 | `EML_TEMPL_NAME` | CHAR | 20 |  | Function of the email |
| 3 | `LANGU` | LANG | 1 |  | Language Key |
| 4 | `VAR_LIST` | TTYP | 0 |  | List of ZISCS_EEC_EML_VAR_VALUE |
