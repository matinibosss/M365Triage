# Case view: it.admin@evilcorp.com

## Summary
- Sign-ins: success=15 fail=19 distinct_ips=7

## Recent timeline (last 200 events)
| ts                        | src    | ip             | action | detail                                                                                                                        | ref  |
| ------------------------- | ------ | -------------- | ------ | ----------------------------------------------------------------------------------------------------------------------------- | ---- |
| 2025-12-12T19:32:00+00:00 | signin | 5.62.41.22     | signin | app=Graph Explorer client=IMAP4 status=50074 result=50074 ec=50074 fr=Token issuer anomaly detected.                          | 4:18 |
| 2025-12-14T07:16:00+00:00 | signin | 5.62.41.22     | signin | app=SharePoint Online client=Browser status=0 result=0                                                                        | 6:23 |
| 2025-12-14T13:06:00+00:00 | signin | 185.199.110.42 | signin | app=Exchange Online client=Browser status=50053 result=50053 ec=50053 fr=Token issuer anomaly detected.                       | 7:4  |
| 2025-12-14T15:31:00+00:00 | signin | 83.45.12.33    | signin | app=Microsoft Teams client=Browser status=50074 result=50074 ec=50074 fr=Invalid username or password.                        | 4:21 |
| 2025-12-16T15:07:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft 365 Admin Center client=Other clients status=0 result=0                                                         | 4:16 |
| 2025-12-18T01:18:00+00:00 | signin | 20.190.128.12  | signin | app=Azure Portal client=Browser status=0 result=0                                                                             | 6:25 |
| 2025-12-18T09:30:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft 365 Admin Center client=Exchange ActiveSync status=50058 result=50058 ec=50058 fr=Invalid username or password. | 7:11 |
| 2025-12-19T02:42:00+00:00 | signin | 20.190.128.12  | signin | app=Microsoft 365 Admin Center client=Browser status=50058 result=50058 ec=50058 fr=Invalid username or password.             | 6:26 |
| 2025-12-20T17:18:00+00:00 | signin | 2.139.88.10    | signin | app=Azure Portal client=IMAP4 status=0 result=0                                                                               | 3:27 |
| 2025-12-20T21:39:00+00:00 | ual    | 5.62.41.22     | ual    | op=FileDownloaded workload=SharePoint                                                                                         | 1:10 |
| 2025-12-21T08:42:00+00:00 | signin | 2.139.88.10    | signin | app=Azure Portal client=Exchange ActiveSync status=50058 result=50058 ec=50058 fr=User did not complete MFA.                  | 7:14 |
| 2025-12-21T10:05:00+00:00 | signin | 20.190.128.12  | signin | app=Microsoft Graph client= status=0 result=0                                                                                 | 5:5  |
| 2025-12-21T15:57:00+00:00 | signin | 20.190.128.12  | signin | app=Microsoft 365 Admin Center client=Browser status=0 result=0                                                               | 4:1  |
| 2025-12-21T16:28:00+00:00 | signin | 83.45.12.34    | signin | app=Exchange Online client=Mobile Apps and Desktop clients status=50053 result=50053 ec=50053 fr=User did not complete MFA.   | 3:8  |
| 2025-12-21T18:14:00+00:00 | signin | 104.26.12.88   | signin | app=Graph Explorer client=Exchange ActiveSync status=50053 result=50053 ec=50053 fr=User did not complete MFA.                | 6:13 |
| 2025-12-22T03:40:00+00:00 | signin | 20.190.128.12  | signin | app=Microsoft Graph client= status=0 result=0                                                                                 | 5:2  |
| 2025-12-23T01:31:00+00:00 | ual    | 185.199.110.42 | ual    | op=FileAccessed workload=SharePoint                                                                                           | 1:30 |
| 2025-12-23T01:41:00+00:00 | signin | 2.139.88.10    | signin | app=Graph Explorer client=IMAP4 status=50076 result=50076 ec=50076 fr=Invalid username or password.                           | 4:17 |
| 2025-12-23T07:31:00+00:00 | signin | 83.45.12.34    | signin | app=Graph Explorer client=POP3 status=0 result=0                                                                              | 7:16 |
| 2025-12-23T13:18:00+00:00 | signin | 83.45.12.33    | signin | app=Graph Explorer client=Mobile Apps and Desktop clients status=50076 result=50076 ec=50076 fr=User did not complete MFA.    | 3:21 |
| 2025-12-24T03:17:00+00:00 | signin | 83.45.12.34    | signin | app=Microsoft Teams client=POP3 status=0 result=0                                                                             | 6:8  |
| 2025-12-24T04:18:00+00:00 | ual    | 83.45.12.33    | ual    | op=Consent to application workload=AzureActiveDirectory                                                                       | 1:23 |
| 2025-12-25T00:18:00+00:00 | signin | 20.190.128.12  | signin | app=SharePoint Online client=IMAP4 status=50076 result=50076 ec=50076 fr=Invalid username or password.                        | 4:24 |
| 2025-12-26T07:33:00+00:00 | signin | 2.139.88.10    | signin | app=Azure Portal client=Exchange ActiveSync status=50058 result=50058 ec=50058 fr=Account is locked.                          | 6:30 |
| 2025-12-26T13:45:00+00:00 | ual    | 5.62.41.22     | ual    | op=MailItemsAccessed workload=Exchange                                                                                        | 1:27 |
| 2025-12-29T09:57:00+00:00 | signin | 104.26.12.88   | signin | app=Microsoft Teams client=Browser status=0 result=0                                                                          | 4:22 |
| 2025-12-29T11:05:00+00:00 | signin | 83.45.12.33    | signin | app=Microsoft Teams client=Exchange ActiveSync status=50074 result=50074 ec=50074 fr=Token issuer anomaly detected.           | 7:8  |
| 2025-12-29T13:12:00+00:00 | signin | 185.199.110.42 | signin | app=Microsoft 365 Admin Center client=IMAP4 status=0 result=0                                                                 | 3:20 |
| 2025-12-29T19:26:00+00:00 | signin | 83.45.12.33    | signin | app=Azure Portal client=Other clients status=50058 result=50058 ec=50058 fr=Token issuer anomaly detected.                    | 4:26 |
| 2025-12-30T14:11:00+00:00 | signin | 2.139.88.10    | signin | app=Exchange Online client=Other clients status=0 result=0                                                                    | 3:25 |
| 2025-12-30T17:33:00+00:00 | signin | 2.139.88.10    | signin | app=Microsoft Graph client= status=0 result=0                                                                                 | 5:16 |
| 2026-01-01T05:56:00+00:00 | signin | 104.26.12.88   | signin | app=Exchange Online client=Other clients status=50074 result=50074 ec=50074 fr=Token issuer anomaly detected.                 | 7:5  |
| 2026-01-01T15:51:00+00:00 | signin | 83.45.12.34    | signin | app=Exchange Online client=Mobile Apps and Desktop clients status=50058 result=50058 ec=50058 fr=Account is locked.           | 7:18 |
| 2026-01-02T02:56:00+00:00 | signin | 185.199.110.42 | signin | app=Microsoft Teams client=Browser status=50053 result=50053 ec=50053 fr=MFA required.                                        | 7:28 |
| 2026-01-02T05:27:00+00:00 | signin | 2.139.88.10    | signin | app=Microsoft Teams client=Mobile Apps and Desktop clients status=0 result=0                                                  | 6:16 |
| 2026-01-03T00:56:00+00:00 | signin | 185.199.110.42 | signin | app=Microsoft 365 Admin Center client=POP3 status=0 result=0                                                                  | 3:17 |
| 2026-01-04T01:18:00+00:00 | signin | 104.26.12.88   | signin | app=SharePoint Online client=Other clients status=50058 result=50058 ec=50058 fr=MFA required.                                | 7:3  |
| 2026-01-05T02:19:00+00:00 | signin | 104.26.12.88   | signin | app=Microsoft 365 Admin Center client=IMAP4 status=50053 result=50053 ec=50053 fr=Account is locked.                          | 6:29 |
| 2026-01-05T03:53:00+00:00 | ual    | 5.62.41.22     | ual    | op=Send workload=Exchange                                                                                                     | 1:1  |