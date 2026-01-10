# M365 Offline Forensic Triage Report

## Coverage
- Global start (UTC): 
- Global end (UTC): 

## Findings summary
| severity | count |
| -------- | ----- |
| medium   | 67    |
| high     | 59    |

## Top categories
| category                 | count |
| ------------------------ | ----- |
| legacy_auth              | 74    |
| risky_signin             | 36    |
| ual_suspicious_operation | 16    |

## High severity findings (top 50)
| timestamp                 | category                 | title                                         | user                    | ip             | details                                                                                                                          |
| ------------------------- | ------------------------ | --------------------------------------------- | ----------------------- | -------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| 2026-01-01T18:23:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | svc.backup@evilcorp.com | 5.62.41.22     | risk_level=high risk_state=atRisk risk_detail=tokenIssuerAnomaly app=Azure Portal client=Mobile Apps and Desktop clients         |
| 2025-12-26T03:16:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | svc.backup@evilcorp.com | 5.62.41.22     | risk_level=medium risk_state=atRisk risk_detail=tokenIssuerAnomaly app=Microsoft Teams client=Mobile Apps and Desktop clients    |
| 2025-12-14T14:07:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | cfo@evilcorp.com        | 5.62.41.22     | risk_level=medium risk_state=atRisk risk_detail=passwordSpray app=SharePoint Online client=Browser                               |
| 2025-12-21T11:21:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | bob@evilcorp.com        | 83.45.12.34    | risk_level=high risk_state=remediated risk_detail=passwordSpray app=Exchange Online client=Other clients                         |
| 2025-12-11T21:25:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | bob@evilcorp.com        | 83.45.12.33    | risk_level=medium risk_state=remediated risk_detail=tokenIssuerAnomaly app=Azure Portal client=IMAP4                             |
| 2026-01-03T15:01:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | bob@evilcorp.com        | 83.45.12.33    | risk_level=high risk_state=atRisk risk_detail=impossibleTravel app=SharePoint Online client=IMAP4                                |
| 2025-12-29T02:40:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | cfo@evilcorp.com        | 20.190.128.12  | risk_level=high risk_state=atRisk risk_detail=passwordSpray app=Exchange Online client=Exchange ActiveSync                       |
| 2025-12-20T17:18:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | it.admin@evilcorp.com   | 2.139.88.10    | risk_level=medium risk_state=remediated risk_detail=passwordSpray app=Azure Portal client=IMAP4                                  |
| 2025-12-19T19:10:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | bob@evilcorp.com        | 20.190.128.12  | risk_level=medium risk_state=confirmedSafe risk_detail=passwordSpray app=Azure Portal client=IMAP4                               |
| 2025-12-12T00:03:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | cfo@evilcorp.com        | 104.26.12.88   | risk_level=medium risk_state=confirmedSafe risk_detail=tokenIssuerAnomaly app=Azure Portal client=Exchange ActiveSync            |
| 2025-12-16T04:16:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | alice@evilcorp.com      | 20.190.128.12  | risk_level=medium risk_state=remediated risk_detail=anonymousIPAddress app=Microsoft 365 Admin Center client=Exchange ActiveSync |
| 2025-12-13T21:36:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | bob@evilcorp.com        | 83.45.12.34    | risk_level=medium risk_state=confirmedSafe risk_detail=passwordSpray app=Microsoft Teams client=Browser                          |
| 2025-12-21T18:14:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | it.admin@evilcorp.com   | 104.26.12.88   | risk_level=medium risk_state=remediated risk_detail=tokenIssuerAnomaly app=Graph Explorer client=Exchange ActiveSync             |
| 2025-12-24T21:00:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | bob@evilcorp.com        | 2.139.88.10    | risk_level=medium risk_state=atRisk risk_detail=anonymousIPAddress app=Exchange Online client=Other clients                      |
| 2025-12-11T12:09:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | alice@evilcorp.com      | 20.190.128.12  | risk_level=medium risk_state=atRisk risk_detail=impossibleTravel app=Microsoft Teams client=POP3                                 |
| 2025-12-23T11:39:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | svc.backup@evilcorp.com | 104.26.12.88   | risk_level=medium risk_state=remediated risk_detail=unfamiliarFeatures app=Azure Portal client=Mobile Apps and Desktop clients   |
| 2025-12-18T19:04:00+00:00 | risky_signin             | Risky sign-in flagged by Entra risk fields    | svc.backup@evilcorp.com | 104.26.12.88   | risk_level=medium risk_state=remediated risk_detail=passwordSpray app=Azure Portal client=Browser                                |
| 2025-12-12T21:47:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | bob@evilcorp.com        | 5.62.41.22     | legacy_client='Other clients' app='Graph Explorer' success=True                                                                  |
| 2025-12-23T15:16:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | svc.backup@evilcorp.com | 185.199.110.42 | legacy_client='Exchange ActiveSync' app='Azure Portal' success=True                                                              |
| 2026-01-03T00:56:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | it.admin@evilcorp.com   | 185.199.110.42 | legacy_client='POP3' app='Microsoft 365 Admin Center' success=True                                                               |
| 2026-01-04T03:10:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | alice@evilcorp.com      | 185.199.110.42 | legacy_client='POP3' app='Exchange Online' success=True                                                                          |
| 2025-12-29T13:12:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | it.admin@evilcorp.com   | 185.199.110.42 | legacy_client='IMAP4' app='Microsoft 365 Admin Center' success=True                                                              |
| 2025-12-20T10:32:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | cfo@evilcorp.com        | 185.199.110.42 | legacy_client='Other clients' app='SharePoint Online' success=True                                                               |
| 2025-12-30T14:11:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | it.admin@evilcorp.com   | 2.139.88.10    | legacy_client='Other clients' app='Exchange Online' success=True                                                                 |
| 2025-12-20T17:18:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | it.admin@evilcorp.com   | 2.139.88.10    | legacy_client='IMAP4' app='Azure Portal' success=True                                                                            |
| 2025-12-18T08:10:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | cfo@evilcorp.com        | 5.62.41.22     | legacy_client='Other clients' app='Azure Portal' success=True                                                                    |
| 2025-12-16T20:04:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | cfo@evilcorp.com        | 83.45.12.34    | legacy_client='Exchange ActiveSync' app='SharePoint Online' success=True                                                         |
| 2025-12-11T15:19:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | cfo@evilcorp.com        | 185.199.110.42 | legacy_client='IMAP4' app='Exchange Online' success=True                                                                         |
| 2025-12-16T04:16:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | alice@evilcorp.com      | 20.190.128.12  | legacy_client='Exchange ActiveSync' app='Microsoft 365 Admin Center' success=True                                                |
| 2025-12-28T21:32:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | bob@evilcorp.com        | 185.199.110.42 | legacy_client='Other clients' app='Microsoft Teams' success=True                                                                 |
| 2025-12-16T15:07:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | it.admin@evilcorp.com   | 5.62.41.22     | legacy_client='Other clients' app='Microsoft 365 Admin Center' success=True                                                      |
| 2025-12-20T15:55:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | cfo@evilcorp.com        | 83.45.12.33    | legacy_client='Other clients' app='Azure Portal' success=True                                                                    |
| 2025-12-24T03:59:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | svc.backup@evilcorp.com | 83.45.12.34    | legacy_client='Other clients' app='Exchange Online' success=True                                                                 |
| 2025-12-13T18:42:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | cfo@evilcorp.com        | 83.45.12.34    | legacy_client='Other clients' app='Microsoft 365 Admin Center' success=True                                                      |
| 2025-12-13T04:05:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | bob@evilcorp.com        | 20.190.128.12  | legacy_client='Exchange ActiveSync' app='SharePoint Online' success=True                                                         |
| 2025-12-24T03:17:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | it.admin@evilcorp.com   | 83.45.12.34    | legacy_client='POP3' app='Microsoft Teams' success=True                                                                          |
| 2025-12-31T15:18:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | cfo@evilcorp.com        | 104.26.12.88   | legacy_client='IMAP4' app='Microsoft Teams' success=True                                                                         |
| 2025-12-12T04:49:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | alice@evilcorp.com      | 83.45.12.34    | legacy_client='IMAP4' app='SharePoint Online' success=True                                                                       |
| 2025-12-24T03:36:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | svc.backup@evilcorp.com | 2.139.88.10    | legacy_client='Exchange ActiveSync' app='Graph Explorer' success=True                                                            |
| 2025-12-24T06:24:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | alice@evilcorp.com      | 185.199.110.42 | legacy_client='IMAP4' app='Exchange Online' success=True                                                                         |
| 2025-12-12T17:02:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | cfo@evilcorp.com        | 5.62.41.22     | legacy_client='Exchange ActiveSync' app='Azure Portal' success=True                                                              |
| 2025-12-21T00:41:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | cfo@evilcorp.com        | 185.199.110.42 | legacy_client='Other clients' app='Microsoft 365 Admin Center' success=True                                                      |
| 2026-01-02T03:48:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | bob@evilcorp.com        | 83.45.12.34    | legacy_client='Exchange ActiveSync' app='Graph Explorer' success=True                                                            |
| 2025-12-23T07:31:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | it.admin@evilcorp.com   | 83.45.12.34    | legacy_client='POP3' app='Graph Explorer' success=True                                                                           |
| 2025-12-28T21:51:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | alice@evilcorp.com      | 2.139.88.10    | legacy_client='Exchange ActiveSync' app='Microsoft Teams' success=True                                                           |
| 2025-12-25T07:03:00+00:00 | legacy_auth              | Legacy authentication / risky client protocol | alice@evilcorp.com      | 5.62.41.22     | legacy_client='IMAP4' app='Azure Portal' success=True                                                                            |
| 2025-12-22T03:59:00+00:00 | ual_suspicious_operation | Suspicious Unified Audit Log operation        | bob@evilcorp.com        | 185.199.110.42 | operation=Set-Mailbox workload=Exchange record_type=1 forwarding_indicator=true                                                  |
| 2025-12-13T21:30:00+00:00 | ual_suspicious_operation | Suspicious Unified Audit Log operation        | svc.backup@evilcorp.com | 20.190.128.12  | operation=Add service principal workload=AzureActiveDirectory record_type=8 dangerous_scopes=['files.read', 'sites.read.all']    |
| 2025-12-12T15:14:00+00:00 | ual_suspicious_operation | Suspicious Unified Audit Log operation        | bob@evilcorp.com        | 2.139.88.10    | operation=Consent to application workload=AzureActiveDirectory record_type=8 dangerous_scopes=['mail.read']                      |
| 2025-12-14T19:05:00+00:00 | ual_suspicious_operation | Suspicious Unified Audit Log operation        | svc.backup@evilcorp.com | 83.45.12.33    | operation=Consent to application workload=AzureActiveDirectory record_type=8 dangerous_scopes=['mail.read']                      |

## Sign-in failures: top IPs
| ip             | fails |
| -------------- | ----- |
| 20.190.128.12  | 17    |
| 2.139.88.10    | 16    |
| 83.45.12.33    | 16    |
| 104.26.12.88   | 12    |
| 83.45.12.34    | 12    |
| 5.62.41.22     | 11    |
| 185.199.110.42 | 9     |

## Sign-in failures: top users
| user                    | fails |
| ----------------------- | ----- |
| cfo@evilcorp.com        | 20    |
| it.admin@evilcorp.com   | 19    |
| alice@evilcorp.com      | 14    |
| svc.backup@evilcorp.com | 14    |
| bob@evilcorp.com        | 13    |

## BEC indicators (summary)
- Forwarding-related events: 4
- Inbox-rule-related events: 1
- Delegation/permissions events: 0

### Top external domains seen in forwarding artifacts
| domain       | count |
| ------------ | ----- |
| evilcorp.com | 8     |
| evil.example | 1     |

## Notes / Next steps
- Review HIGH findings first, then correlate with mailbox content checks, inbox rules, and suspicious OAuth consents.
- If you have additional logs (Defender for Office 365, Mailflow, EDR), ingest them for better correlation.
