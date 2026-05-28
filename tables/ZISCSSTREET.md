# ZISCSSTREET
**Description:** Street
**Total Fields:** 13
**Key Fields:** MANDT, FUNC_LOC

## Programs Using This Table
- `ziscs0201`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FUNC_LOC` | CHAR | 30 | 🔑 | Connection object number |
| 3 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 4 | `DISTRICT` | CHAR | 40 |  | District, the address line with ADRC-nation = space |
| 5 | `DISTRICT_C` | CHAR | 40 |  | District in Chinese, the address line with ADRC-nation = 'M' |
| 6 | `STREET` | CHAR | 60 |  | Street, the address line with ADRC-nation = space |
| 7 | `STREET_C` | CHAR | 60 |  | Street in Chinese, the address line with ADRC-nation = 'M' |
| 8 | `HOUSE_NUMBER` | CHAR | 10 |  | House number, the address line with ADRC-nation = space |
| 9 | `HOUSE_NUMBER_C` | CHAR | 10 |  | House no in Chinese, the address line with ADRC-nation = 'M' |
| 10 | `STREET2` | CHAR | 40 |  | Street 2, the address line with ADRC-nation = space |
| 11 | `STREET2_C` | CHAR | 40 |  | Street 2 in Chinese, the address line with ADRC-nation = 'M' |
| 12 | `STREET3` | CHAR | 40 |  | Street 3 |
| 13 | `STREET3_C` | CHAR | 40 |  | Street 3 in Chinese |
