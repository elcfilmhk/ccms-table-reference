# ZISCS_PON_CA_EXPORT
**Description:** Export File structure for Proactive Outage Notification Sys.
**Total Fields:** 20
**Key Fields:** _none_

## Programs Using This Table
- `ziscs_pon_export_ca`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `PREFERRED_LANG` | CHAR | 2 |  | Version Number Component |
| 3 | `HAUS` | CHAR | 30 |  | Connection Object |
| 4 | `VSTELLE` | CHAR | 10 |  | Premise |
| 5 | `VBSART` | CHAR | 8 |  | Type of premise |
| 6 | `TELEPHONE` | CHAR | 30 |  | 30 Characters |
| 7 | `EMAIL_ADDR` | CHAR | 255 |  | Attribute 1 for Contact Information |
| 8 | `DEVICETOKEN` | CHAR | 256 |  | The push notification token of mobile device (Pass from App) |
| 9 | `DEVICETYPE` | CHAR | 1 |  | Device Type (iPhone or Android) |
| 10 | `STREET` | CHAR | 60 |  | Street |
| 11 | `STREET_M` | CHAR | 60 |  | Street |
| 12 | `STREET5` | CHAR | 40 |  | Street 5 |
| 13 | `STREET5_M` | CHAR | 40 |  | Street 5 |
| 14 | `CITY2` | CHAR | 40 |  | District |
| 15 | `CITY2_M` | CHAR | 40 |  | District |
| 16 | `DO_NOT_SEND` | CHAR | 1 |  | Single-Character Flag |
| 17 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 18 | `AMI_METER_FLAG` | CHAR | 1 |  | Single-Character Flag |
| 19 | `LAST_GASP_FLAG` | CHAR | 1 |  | Single-Character Flag |
| 20 | `SERNR` | CHAR | 18 |  | Serial Number |
