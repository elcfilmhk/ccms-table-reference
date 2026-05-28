# ZISBICONOBJ
**Description:** The Connection Object Selection Criteria
**Total Fields:** 10
**Key Fields:** MANDT, CONN_SELCRI_NO

## Programs Using This Table
- `zisbi0003`
- `zisbi0005`
- `zisbi0059`
- `zisbi0060`
- `zisbi0138`
- `zisbi_conv_selcri_temp`
- `ziscs0288`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONN_SELCRI_NO` | NUMC | 10 | 🔑 | The selection criteria number |
| 3 | `CITY` | CHAR | 255 |  | The city |
| 4 | `DISTRICT` | CHAR | 255 |  | The district |
| 5 | `AREA` | CHAR | 255 |  | The area |
| 6 | `GROUP1` | CHAR | 255 |  | The group |
| 7 | `POLITICAL` | CHAR | 255 |  | The political structure |
| 8 | `STREET` | CHAR | 255 |  | The Street |
| 9 | `STREET2` | CHAR | 255 |  | The Street2 |
| 10 | `HOUSE_NO` | CHAR | 100 |  | The house number |
