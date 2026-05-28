# ZISMDEXCEPT
**Description:** Storing the installation & meter in exceptiion list
**Total Fields:** 4
**Key Fields:** MANDT, TYPE, VALUE

## Programs Using This Table
- `zisdm0027`
- `zisdm0184`
- `zisdm0212`
- `zisdm0214`
- `zised0041`
- `zised0047`
- `zised0049`
- `zised0064`
- `zismd0036`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TYPE` | CHAR | 1 | 🔑 | Specifies the type of the value store in ZISMDEXCEPT |
| 3 | `VALUE` | CHAR | 18 | 🔑 | Stores the value of the data, i.e. Installation / Meter |
| 4 | `REMARK` | CHAR | 50 |  | Remark |
