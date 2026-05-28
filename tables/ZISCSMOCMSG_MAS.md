# ZISCSMOCMSG_MAS
**Description:** Managed Outbound Communication Message Transaction Table
**Total Fields:** 36
**Key Fields:** MANDT, VKONT, CREATION_DATE, MESSAGETYPE, SUB_MESSAGE_TYPE, DISPATCH, COUNTER

## Programs Using This Table
- `z_iscsget_pref_comm_chnl======ft`
- `zcl_process_inbound_email`
- `ziscrm0318`
- `ziscs0528`
- `ziscs0726`
- `ziscs0730`
- `ziscs0826`
- `zisdm0355`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CREATION_DATE` | DATS | 8 | 🔑 | Creation Date |
| 4 | `MESSAGETYPE` | CHAR | 2 | 🔑 | Message Type |
| 5 | `SUB_MESSAGE_TYPE` | CHAR | 3 | 🔑 | Sub Message Type |
| 6 | `DISPATCH` | CHAR | 1 | 🔑 | Dispatch |
| 7 | `COUNTER` | NUMC | 5 | 🔑 | Counter |
| 8 | `HDR_COUNTER` | NUMC | 5 |  | HDR Counter |
| 9 | `MESSAGETEMPLATE` | CHAR | 20 |  | Template Name for Email, SMS or MPush message |
| 10 | `LANGUAGE` | LANG | 1 |  | Language Key |
| 11 | `GENERIC_DATA_1` | CHAR | 100 |  | Generic Data |
| 12 | `GENERIC_DATA_2` | CHAR | 100 |  | Generic Data |
| 13 | `COMMCHANNEL_PRMTR` | CHAR | 256 |  | Communication Channel Parameter(Email,Mobile or DeviceToken) |
| 14 | `COMMCHANNEL_PRMTR_TO_1` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 15 | `COMMCHANNEL_PRMTR_TO_2` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 16 | `COMMCHANNEL_PRMTR_CC_1` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 17 | `COMMCHANNEL_PRMTR_CC_2` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 18 | `COMMCHANNEL_PRMTR_CC_3` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 19 | `COMMCHANNEL_PRMTR_CC_4` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 20 | `COMMCHANNEL_PRMTR_CC_5` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 21 | `COMMCHANNEL_PRMTR_CC_6` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 22 | `COMMCHANNEL_PRMTR_CC_7` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 23 | `COMMCHANNEL_PRMTR_CC_8` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 24 | `COMMCHANNEL_PRMTR_CC_9` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 25 | `COMMCHANNEL_PRMTR_CC_10` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 26 | `RE_APP_NO` | CHAR | 12 |  | Notification No |
| 27 | `MSGSEND_STATUS` | CHAR | 2 |  | Status of Sent message |
| 28 | `MSGSEND_DATE` | DATS | 8 |  | Message Send Date |
| 29 | `MSGSEND_TIME` | TIMS | 6 |  | Message Send Time |
| 30 | `MSGRESP_STATUS` | CHAR | 10 |  | Status of Response Message |
| 31 | `MSGRESP_DATE` | DATS | 8 |  | Message response date |
| 32 | `MSGRESP_TIME` | TIMS | 6 |  | Message response time |
| 33 | `EXTERNAL_REF` | CHAR | 32 |  | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 34 | `RESPONSE_INFO` | CHAR | 300 |  | Text |
| 35 | `COMMCHANNEL_PRMTR_BCC_1` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 36 | `DR_REF_GUID` | CHAR | 32 |  | 16 Byte UUID in 32 Characters (Hexadecimal Encoded) |
