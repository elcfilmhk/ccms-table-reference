# ZISMDEAIXML
**Description:** XML generation for meter installation to to eai interface
**Total Fields:** 75
**Key Fields:** _none_

## Programs Using This Table
- `zismd0030`
- `zismd0032`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SEQUENCE` | CHAR | 10 |  | MDMS 10 Characters |
| 2 | `OPERATIONTYPE` | CHAR | 20 |  | MDMS 20 Characters |
| 3 | `SERVICEPOINTID` | CHAR | 50 |  | Point of delivery ID |
| 4 | `TIMEZONE` | CHAR | 20 |  | MDMS 20 Characters |
| 5 | `SERVICEPOINTPROGRAMID` | CHAR | 20 |  | MDMS Service point program |
| 6 | `METERID` | CHAR | 18 |  | Serial Number |
| 7 | `METERNUMBER` | CHAR | 18 |  | Serial Number |
| 8 | `DATEINITIALIZED` | CHAR | 8 |  | MDMS date |
| 9 | `INSTALLDATE` | CHAR | 8 |  | MDMS date |
| 10 | `LOCATIONCODE` | CHAR | 30 |  | Addition to device location |
| 11 | `BATTERYINSTALLDATE` | CHAR | 8 |  | MDMS date |
| 12 | `MINUTESONBATTERY` | CHAR | 1 |  | MDMS 1 character |
| 13 | `DAYSONBATTERY` | CHAR | 1 |  | MDMS 1 character |
| 14 | `METERPROGRAMID` | CHAR | 20 |  | MDMS Meter Program |
| 15 | `CONTACTFORM` | CHAR | 1 |  | MDMS 1 character |
| 16 | `ENDPOINTID` | CHAR | 18 |  | Serial Number |
| 17 | `EXTERNALSYSTEMID` | CHAR | 50 |  | MDMS server name |
| 18 | `CTRATIO` | CHAR | 10 |  | MDMS 10 Characters |
| 19 | `PTRATIO` | CHAR | 10 |  | MDMS 10 Characters |
| 20 | `PHASECODE` | CHAR | 16 |  | MDMD 16 characters |
| 21 | `PRESSURECOMPENSATIONFACTOR` | CHAR | 10 |  | MDMS 10 Characters |
| 22 | `SERVICETYPE` | CHAR | 10 |  | MDMS 10 Characters |
| 23 | `EFFECTIVESTARTDATE` | CHAR | 8 |  | MDMS date |
| 24 | `ADDRESSLINE1` | CHAR | 200 |  | MDMS Address Line |
| 25 | `ADDRESSLINE2` | CHAR | 200 |  | MDMS Address Line |
| 26 | `CITY` | CHAR | 40 |  | District |
| 27 | `COUNTY` | CHAR | 40 |  | City |
| 28 | `STATE` | CHAR | 10 |  | MDMS 10 Characters |
| 29 | `PROVINCE` | CHAR | 40 |  | City |
| 30 | `COUNTRY` | CHAR | 15 |  | Country Name |
| 31 | `CHANGEDATE` | CHAR | 8 |  | MDMS date |
| 32 | `DECOMMISSIONMETER` | CHAR | 10 |  | MDMS 10 Characters |
| 33 | `DEVICEID` | CHAR | 50 |  | MDMS 50 characters |
| 34 | `CURRENTMETERID` | CHAR | 18 |  | Serial Number |
| 35 | `METERSTATUS` | CHAR | 20 |  | MDMS 20 Characters |
| 36 | `NAME01` | CHAR | 50 |  | MDMS 50 characters |
| 37 | `VALUE01` | CHAR | 50 |  | MDMS 50 characters |
| 38 | `NAME02` | CHAR | 50 |  | MDMS 50 characters |
| 39 | `VALUE02` | CHAR | 50 |  | MDMS 50 characters |
| 40 | `NAME03` | CHAR | 50 |  | MDMS 50 characters |
| 41 | `VALUE03` | CHAR | 50 |  | MDMS 50 characters |
| 42 | `NAME04` | CHAR | 50 |  | MDMS 50 characters |
| 43 | `VALUE04` | CHAR | 50 |  | MDMS 50 characters |
| 44 | `NAME05` | CHAR | 50 |  | MDMS 50 characters |
| 45 | `VALUE05` | CHAR | 50 |  | MDMS 50 characters |
| 46 | `NAME06` | CHAR | 50 |  | MDMS 50 characters |
| 47 | `VALUE06` | CHAR | 50 |  | MDMS 50 characters |
| 48 | `NAME07` | CHAR | 50 |  | MDMS 50 characters |
| 49 | `VALUE07` | CHAR | 50 |  | MDMS 50 characters |
| 50 | `NAME08` | CHAR | 50 |  | MDMS 50 characters |
| 51 | `VALUE08` | CHAR | 50 |  | MDMS 50 characters |
| 52 | `NAME09` | CHAR | 50 |  | MDMS 50 characters |
| 53 | `VALUE09` | CHAR | 50 |  | MDMS 50 characters |
| 54 | `NAME10` | CHAR | 50 |  | MDMS 50 characters |
| 55 | `VALUE10` | CHAR | 50 |  | MDMS 50 characters |
| 56 | `NAME11` | CHAR | 50 |  | MDMS 50 characters |
| 57 | `VALUE11` | CHAR | 50 |  | MDMS 50 characters |
| 58 | `NAME12` | CHAR | 50 |  | MDMS 50 characters |
| 59 | `VALUE12` | CHAR | 50 |  | MDMS 50 characters |
| 60 | `NAME13` | CHAR | 50 |  | MDMS 50 characters |
| 61 | `VALUE13` | CHAR | 50 |  | MDMS 50 characters |
| 62 | `NAME14` | CHAR | 50 |  | MDMS 50 characters |
| 63 | `VALUE14` | CHAR | 50 |  | MDMS 50 characters |
| 64 | `NAME15` | CHAR | 50 |  | MDMS 50 characters |
| 65 | `VALUE15` | CHAR | 50 |  | MDMS 50 characters |
| 66 | `NAME16` | CHAR | 50 |  | MDMS 50 characters |
| 67 | `VALUE16` | CHAR | 50 |  | MDMS 50 characters |
| 68 | `NAME17` | CHAR | 50 |  | MDMS 50 characters |
| 69 | `VALUE17` | CHAR | 50 |  | MDMS 50 characters |
| 70 | `NAME18` | CHAR | 50 |  | MDMS 50 characters |
| 71 | `VALUE18` | CHAR | 50 |  | MDMS 50 characters |
| 72 | `NAME19` | CHAR | 50 |  | MDMS 50 characters |
| 73 | `VALUE19` | CHAR | 50 |  | MDMS 50 characters |
| 74 | `NAME20` | CHAR | 50 |  | MDMS 50 characters |
| 75 | `VALUE20` | CHAR | 50 |  | MDMS 50 characters |
