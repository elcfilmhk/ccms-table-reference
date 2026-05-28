# ZISCRM_CAMPAIGN_FOR_ALERT
**Description:** Campaign Data for Alert
**Total Fields:** 16
**Key Fields:** _none_

## Programs Using This Table
- `zalertmsg`
- `ziscs0307`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TASK_GUID` | RAW | 16 |  | Project Planning: 16 Character GUID for Tasks |
| 2 | `EXTERNAL_ID` | CHAR | 24 |  | Project Planning: External Indentifier of an Element |
| 3 | `PROJECT_GUID` | RAW | 16 |  | Project Planning: 16 Character GUID for Projects |
| 4 | `DESCRIPTION` | CHAR | 40 |  | Language-Dependent Short Text |
| 5 | `START_DATE` | CHAR | 10 |  | Start Date |
| 6 | `END_DATE` | CHAR | 10 |  | End Date |
| 7 | `BUAG_ID` | CHAR | 12 |  | Business Agreement Number |
| 8 | `BUAG_GUID` | RAW | 16 |  | Business Agreement GUID |
| 9 | `ACTIVITY_GUID` | RAW | 16 |  | GUID of a CRM Order Object |
| 10 | `ACTIVITY_OBJECT_ID` | CHAR | 10 |  | Transaction ID |
| 11 | `ACTIVITY_RESULT` | CHAR | 40 |  | Activity Result |
| 12 | `ACTIVITY_CATALOG` | CHAR | 2 |  | Catalog |
| 13 | `ACTIVITY_CODEGROUP` | CHAR | 8 |  | Code Group |
| 14 | `ACTIVITY_CODE` | CHAR | 4 |  | Code |
| 15 | `PRIORITY` | NUMC | 3 |  | Campaign Priority |
| 16 | `ALERT_ID` | CHAR | 20 |  | Alert Identifier |
