# ZISBI_PM_ELEM
**Description:** Segmentation - Promotion Elements Config
**Total Fields:** 34
**Key Fields:** MANDT, LOGNUM

## Programs Using This Table
- `zisbi0229`
- `zisbi0231`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOGNUM` | NUMC | 8 | 🔑 | Log number |
| 3 | `AREA` | CHAR | 20 |  | Promotion Area |
| 4 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 5 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 6 | `AUTOPAY` | CHAR | 1 |  | Autopay |
| 7 | `CREDIT_CARD` | CHAR | 1 |  | Credit Card |
| 8 | `CASH` | CHAR | 1 |  | Cash |
| 9 | `ACCOUNT_CLASS` | CHAR | 4 |  | Account class |
| 10 | `RT` | CHAR | 1 |  | RT |
| 11 | `NRT` | CHAR | 1 |  | Non-RT |
| 12 | `BT` | CHAR | 1 |  | BT |
| 13 | `LPT` | CHAR | 1 |  | LPT |
| 14 | `PLT` | CHAR | 1 |  | PLT |
| 15 | `UNMETER` | CHAR | 1 |  | Unmeter |
| 16 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 17 | `DEVELOPER` | CHAR | 1 |  | Developer |
| 18 | `GRP` | CHAR | 1 |  | Group Bill identification |
| 19 | `AMI_GROUP11` | CHAR | 1 |  | AMI Group11 |
| 20 | `AMI_GROUP12` | CHAR | 1 |  | AMI Group12 |
| 21 | `AMI_GROUP13` | CHAR | 1 |  | AMI Group13 |
| 22 | `AMI_GROUP14` | CHAR | 1 |  | AMI Group14 |
| 23 | `CONSENT` | CHAR | 1 |  | With consent |
| 24 | `NOCONSENT` | CHAR | 1 |  | Without consent |
| 25 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 26 | `ACTPERIOD` | CHAR | 4 |  | Category of a period for current billing |
| 27 | `MIDAYS` | NUMC | 8 |  | Move in Days |
| 28 | `IMAGE_LINK_EN` | CHAR | 255 |  | Image Link (Eng) |
| 29 | `IMAGE_LINK_CHI` | CHAR | 255 |  | Image Link (Chi) |
| 30 | `CLICK_LINK_EN` | CHAR | 255 |  | Click Link (Eng) |
| 31 | `CLICK_LINK_CHI` | CHAR | 255 |  | Click Link (Chi) |
| 32 | `DESC_EN` | CHAR | 255 |  | Description (Eng) |
| 33 | `DESC_CHI` | CHAR | 255 |  | Description (Chi) |
| 34 | `SEQUENCE` | NUMC | 3 |  | Sequence |
