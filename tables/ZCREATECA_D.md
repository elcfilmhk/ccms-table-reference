# ZCREATECA_D
**Description:** Automated Move-in details (Developer)
**Total Fields:** 24
**Key Fields:** MANDT, TXNNUM

## Programs Using This Table
- `ziscs0023`
- `ziscs0310`
- `ziscs0312`
- `ziscs0313`
- `ziscs0314`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TXNNUM` | CHAR | 10 | 🔑 | CRM transaction no. |
| 3 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 4 | `HAUS` | CHAR | 30 |  | Connection Object |
| 5 | `METER` | CHAR | 18 |  | Meter installed |
| 6 | `MI_DATE` | DATS | 8 |  | Move-in date |
| 7 | `MI_READING` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 8 | `CUSTOMER_TITLE` | CHAR | 5 |  | Customer Title |
| 9 | `CUSTOMER_NAME` | CHAR | 80 |  | Business Partner Name (English) |
| 10 | `ID_TYPE` | CHAR | 6 |  | BP ID Type |
| 11 | `ID_NUMBER` | CHAR | 60 |  | BP ID No. |
| 12 | `PHONE` | CHAR | 8 |  | Contact Phone No. |
| 13 | `POSTAL_LINE_1` | CHAR | 30 |  | Postal line |
| 14 | `POSTAL_LINE_2` | CHAR | 30 |  | Postal line |
| 15 | `POSTAL_LINE_3` | CHAR | 30 |  | Postal line |
| 16 | `POSTAL_LINE_4` | CHAR | 30 |  | Postal line |
| 17 | `EMAIL` | CHAR | 60 |  | Email Address |
| 18 | `STATUS` | CHAR | 1 |  | Record Status (A, S, R, C, X) |
| 19 | `CREATED_ON` | DATS | 8 |  | Date on Which Record Was Created |
| 20 | `CREATED_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 21 | `CHANGED_ON` | DATS | 8 |  | Date of Last Change |
| 22 | `CHANGED_BY` | CHAR | 12 |  | Name of person who changed object |
| 23 | `RECEIVED` | CHAR | 1 |  | Received |
| 24 | `CONSENT` | CHAR | 1 |  | Consent |
