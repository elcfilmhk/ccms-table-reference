# ZISCS_PON_CA_OUTPUT
**Description:** Output structure for ZISCS_PON_GET_CA
**Total Fields:** 21
**Key Fields:** _none_

## Programs Using This Table
- `ziscs_pon_export_ca`
- `ziscs_pon_get_ca==============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `PREFERRED_LANG` | CHAR | 2 |  | Version Number Component |
| 3 | `ANLAGE` | CHAR | 10 |  | Installation |
| 4 | `HAUS` | CHAR | 30 |  | Connection Object |
| 5 | `VSTELLE` | CHAR | 10 |  | Premise |
| 6 | `VBSART` | CHAR | 8 |  | Type of premise |
| 7 | `TELEPHONE` | CHAR | 30 |  | 30 Characters |
| 8 | `EMAIL_ADDR` | CHAR | 255 |  | Attribute 1 for Contact Information |
| 9 | `DEVICETOKEN` | CHAR | 256 |  | The push notification token of mobile device (Pass from App) |
| 10 | `DEVICETYPE` | CHAR | 1 |  | Device Type (iPhone or Android) |
| 11 | `STREET` | CHAR | 60 |  | Street |
| 12 | `STREET_M` | CHAR | 60 |  | Street |
| 13 | `STREET5` | CHAR | 40 |  | Street 5 |
| 14 | `STREET5_M` | CHAR | 40 |  | Street 5 |
| 15 | `CITY2` | CHAR | 40 |  | District |
| 16 | `CITY2_M` | CHAR | 40 |  | District |
| 17 | `DO_NOT_SEND` | CHAR | 1 |  | Single-Character Flag |
| 18 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 19 | `AMI_METER_FLAG` | CHAR | 1 |  | Single-Character Flag |
| 20 | `LAST_GASP_FLAG` | CHAR | 1 |  | Single-Character Flag |
| 21 | `SERNR` | CHAR | 18 |  | Serial Number |
