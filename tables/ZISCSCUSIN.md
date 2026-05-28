# ZISCSCUSIN
**Description:** CRM to CCS Customer Information
**Total Fields:** 15
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0002`
- `ziscs0049`
- `ziscs0060`
- `ziscs0108`
- `ziscs0169`
- `ziscs0169_old`
- `ziscs0174`
- `ziscs0278`
- `zisdm0017`
- `zisdm0029`
- `zisdm0058`
- `zisdm0059`
- `zisdm0060`
- `zisdm0090`
- `zisdm0091`
- `zisdm0139`
- `zisfi0121`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 2 | `OBJEK` | CHAR | 50 |  | Key of object to be classified |
| 3 | `ATWRT` | CHAR | 30 |  | Characteristic Value |
| 4 | `TYPE` | CHAR | 6 |  | Identification Type |
| 5 | `IDNUMBER` | CHAR | 60 |  | Identification Number |
| 6 | `TEL_NUMBER` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 7 | `CTEL_NUMBER` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 8 | `NAME_LAST` | CHAR | 40 |  | Last name |
| 9 | `NAME_FIRST` | CHAR | 40 |  | First Name of Business Partner (Person) |
| 10 | `NAME_ORG1` | CHAR | 81 |  | Organization Name 1 and Organization Name 2 |
| 11 | `NAME_ORG3` | CHAR | 81 |  | Organization Name 3 and Organization Name 4 |
| 12 | `BP_TYPE` | CHAR | 1 |  | Type of business partner |
| 13 | `STAFFID` | CHAR | 60 |  | Identification Number - Staff |
| 14 | `BP_CHANGED` | CHAR | 1 |  | Single-Character Flag |
| 15 | `TITLE` | CHAR | 4 |  | Form-of-Address Key |
