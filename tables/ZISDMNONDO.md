# ZISDMNONDO
**Description:** Custome table for Non Domestic - LPAS
**Total Fields:** 101
**Key Fields:** MANDT, VKONT, VERTRAG, VSTELLE

## Programs Using This Table
- `zisdm0058`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client ID |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Character Field of Length 12 |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 4 | `VSTELLE` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 5 | `ZPSREGION` | CHAR | 2 |  | Version Number Component |
| 6 | `ZEWMPLANTSEC` | CHAR | 2 |  | Version Number Component |
| 7 | `HAUS` | CHAR | 9 |  | Character field of 9 digits |
| 8 | `LGZUSATZ` | CHAR | 9 |  | Character field of 9 digits |
| 9 | `ZZTARIFTYP` | CHAR | 1 |  | Single-Character Flag |
| 10 | `ZZSUBTRFTY` | CHAR | 1 |  | Single-Character Flag |
| 11 | `TRD_CLASS` | CHAR | 2 |  | Version Number Component |
| 12 | `TRD_SUB_CLASS` | CHAR | 2 |  | Version Number Component |
| 13 | `VBSART` | CHAR | 8 |  | Character field, 8 characters long |
| 14 | `SPEBENE` | CHAR | 10 |  | Character Field Length = 10 |
| 15 | `EINZDAT` | CHAR | 8 |  | Character field, 8 characters long |
| 16 | `AUSZDAT` | CHAR | 8 |  | Character field, 8 characters long |
| 17 | `VKBEZ` | CHAR | 35 |  | Data Element Type CHAR Length 35 |
| 18 | `ADDRESS1` | CHAR | 40 |  | Character field of length 40 |
| 19 | `ADDRESS2` | CHAR | 40 |  | Character field of length 40 |
| 20 | `ADDRESS3` | CHAR | 40 |  | Character field of length 40 |
| 21 | `ADDRESS4` | CHAR | 40 |  | Character field of length 40 |
| 22 | `ADAT_01` | CHAR | 8 |  | Character field, 8 characters long |
| 23 | `ONPEAKCON_01` | CHAR | 13 |  | Character field 13 digits |
| 24 | `OFFPEAKCON_01` | CHAR | 13 |  | Character field 13 digits |
| 25 | `ONDEMAND_01` | CHAR | 13 |  | Character field 13 digits |
| 26 | `OFFDEMAND_01` | CHAR | 13 |  | Character field 13 digits |
| 27 | `ADAT_02` | CHAR | 8 |  | Character field, 8 characters long |
| 28 | `ONPEAKCON_02` | CHAR | 13 |  | Character field 13 digits |
| 29 | `OFFPEAKCON_02` | CHAR | 13 |  | Character field 13 digits |
| 30 | `ONDEMAND_02` | CHAR | 13 |  | Character field 13 digits |
| 31 | `OFFDEMAND_02` | CHAR | 13 |  | Character field 13 digits |
| 32 | `ADAT_03` | CHAR | 8 |  | Character field, 8 characters long |
| 33 | `ONPEAKCON_03` | CHAR | 13 |  | Character field 13 digits |
| 34 | `OFFPEAKCON_03` | CHAR | 13 |  | Character field 13 digits |
| 35 | `ONDEMAND_03` | CHAR | 13 |  | Character field 13 digits |
| 36 | `OFFDEMAND_03` | CHAR | 13 |  | Character field 13 digits |
| 37 | `ADAT_04` | CHAR | 8 |  | Character field, 8 characters long |
| 38 | `ONPEAKCON_04` | CHAR | 13 |  | Character field 13 digits |
| 39 | `OFFPEAKCON_04` | CHAR | 13 |  | Character field 13 digits |
| 40 | `ONDEMAND_04` | CHAR | 13 |  | Character field 13 digits |
| 41 | `OFFDEMAND_04` | CHAR | 13 |  | Character field 13 digits |
| 42 | `ADAT_05` | CHAR | 8 |  | Character field, 8 characters long |
| 43 | `ONPEAKCON_05` | CHAR | 13 |  | Character field 13 digits |
| 44 | `OFFPEAKCON_05` | CHAR | 13 |  | Character field 13 digits |
| 45 | `ONDEMAND_05` | CHAR | 13 |  | Character field 13 digits |
| 46 | `OFFDEMAND_05` | CHAR | 13 |  | Character field 13 digits |
| 47 | `ADAT_06` | CHAR | 8 |  | Character field, 8 characters long |
| 48 | `ONPEAKCON_06` | CHAR | 13 |  | Character field 13 digits |
| 49 | `OFFPEAKCON_06` | CHAR | 13 |  | Character field 13 digits |
| 50 | `ONDEMAND_06` | CHAR | 13 |  | Character field 13 digits |
| 51 | `OFFDEMAND_06` | CHAR | 13 |  | Character field 13 digits |
| 52 | `ADAT_07` | CHAR | 8 |  | Character field, 8 characters long |
| 53 | `ONPEAKCON_07` | CHAR | 13 |  | Character field 13 digits |
| 54 | `OFFPEAKCON_07` | CHAR | 13 |  | Character field 13 digits |
| 55 | `ONDEMAND_07` | CHAR | 13 |  | Character field 13 digits |
| 56 | `OFFDEMAND_07` | CHAR | 13 |  | Character field 13 digits |
| 57 | `ADAT_08` | CHAR | 8 |  | Character field, 8 characters long |
| 58 | `ONPEAKCON_08` | CHAR | 13 |  | Character field 13 digits |
| 59 | `OFFPEAKCON_08` | CHAR | 13 |  | Character field 13 digits |
| 60 | `ONDEMAND_08` | CHAR | 13 |  | Character field 13 digits |
| 61 | `OFFDEMAND_08` | CHAR | 13 |  | Character field 13 digits |
| 62 | `ADAT_09` | CHAR | 8 |  | Character field, 8 characters long |
| 63 | `ONPEAKCON_09` | CHAR | 13 |  | Character field 13 digits |
| 64 | `OFFPEAKCON_09` | CHAR | 13 |  | Character field 13 digits |
| 65 | `ONDEMAND_09` | CHAR | 13 |  | Character field 13 digits |
| 66 | `OFFDEMAND_09` | CHAR | 13 |  | Character field 13 digits |
| 67 | `ADAT_10` | CHAR | 8 |  | Character field, 8 characters long |
| 68 | `ONPEAKCON_10` | CHAR | 13 |  | Character field 13 digits |
| 69 | `OFFPEAKCON_10` | CHAR | 13 |  | Character field 13 digits |
| 70 | `ONDEMAND_10` | CHAR | 13 |  | Character field 13 digits |
| 71 | `OFFDEMAND_10` | CHAR | 13 |  | Character field 13 digits |
| 72 | `ADAT_11` | CHAR | 8 |  | Character field, 8 characters long |
| 73 | `ONPEAKCON_11` | CHAR | 13 |  | Character field 13 digits |
| 74 | `OFFPEAKCON_11` | CHAR | 13 |  | Character field 13 digits |
| 75 | `ONDEMAND_11` | CHAR | 13 |  | Character field 13 digits |
| 76 | `OFFDEMAND_11` | CHAR | 13 |  | Character field 13 digits |
| 77 | `ADAT_12` | CHAR | 8 |  | Character field, 8 characters long |
| 78 | `ONPEAKCON_12` | CHAR | 13 |  | Character field 13 digits |
| 79 | `OFFPEAKCON_12` | CHAR | 13 |  | Character field 13 digits |
| 80 | `ONDEMAND_12` | CHAR | 13 |  | Character field 13 digits |
| 81 | `OFFDEMAND_12` | CHAR | 13 |  | Character field 13 digits |
| 82 | `ADAT_13` | CHAR | 8 |  | Character field, 8 characters long |
| 83 | `ONPEAKCON_13` | CHAR | 13 |  | Character field 13 digits |
| 84 | `OFFPEAKCON_13` | CHAR | 13 |  | Character field 13 digits |
| 85 | `ONDEMAND_13` | CHAR | 13 |  | Character field 13 digits |
| 86 | `OFFDEMAND_13` | CHAR | 13 |  | Character field 13 digits |
| 87 | `ADAT_14` | CHAR | 8 |  | Character field, 8 characters long |
| 88 | `ONPEAKCON_14` | CHAR | 13 |  | Character field 13 digits |
| 89 | `OFFPEAKCON_14` | CHAR | 13 |  | Character field 13 digits |
| 90 | `ONDEMAND_14` | CHAR | 13 |  | Character field 13 digits |
| 91 | `OFFDEMAND_14` | CHAR | 13 |  | Character field 13 digits |
| 92 | `ADAT_15` | CHAR | 8 |  | Character field, 8 characters long |
| 93 | `ONPEAKCON_15` | CHAR | 13 |  | Character field 13 digits |
| 94 | `OFFPEAKCON_15` | CHAR | 13 |  | Character field 13 digits |
| 95 | `ONDEMAND_15` | CHAR | 13 |  | Character field 13 digits |
| 96 | `OFFDEMAND_15` | CHAR | 13 |  | Character field 13 digits |
| 97 | `ADAT_16` | CHAR | 8 |  | Character field, 8 characters long |
| 98 | `ONPEAKCON_16` | CHAR | 13 |  | Character field 13 digits |
| 99 | `OFFPEAKCON_16` | CHAR | 13 |  | Character field 13 digits |
| 100 | `ONDEMAND_16` | CHAR | 13 |  | Character field 13 digits |
| 101 | `OFFDEMAND_16` | CHAR | 13 |  | Character field 13 digits |
