# ZISCSEEC_CAATT_C
**Description:** CA Attribute Category (optional) definition
**Total Fields:** 6
**Key Fields:** MANDT, ATTR_CATEGORY

## Programs Using This Table
- `ziscs0386_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ATTR_CATEGORY` | CHAR | 50 | 🔑 | CA Attribute Category |
| 3 | `LABEL_EN` | CHAR | 50 |  | Label(EN) |
| 4 | `LABEL_ZF` | CHAR | 50 |  | Label(ZF) |
| 5 | `DESC_EN` | CHAR | 200 |  | Description(EN) |
| 6 | `DESC_ZF` | CHAR | 200 |  | Description(ZF) |
