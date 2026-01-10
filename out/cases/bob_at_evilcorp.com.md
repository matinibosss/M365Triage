# Case view: bob@evilcorp.com

## Summary
- Sign-ins: success=10 fail=13 distinct_ips=7

## Recent timeline (last 200 events)
| ts                        | src    | ip             | action | detail                                                                                                                      | ref  |
| ------------------------- | ------ | -------------- | ------ | --------------------------------------------------------------------------------------------------------------------------- | ---- |
| 2025-12-11T21:25:00+00:00 | signin | 83.45.12.33    | signin | app=Azure Portal client=IMAP4 status=50074 result=50074 ec=50074 fr=Token issuer anomaly detected.                          | 3:14 |
| 2025-12-11T23:23:00+00:00 | signin | 20.190.128.12  | signin | app=Azure Resource Manager client= status=0 result=0                                                                        | 5:14 |
| 2025-12-12T10:45:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft Graph client= status=0 result=0                                                                               | 5:3  |
| 2025-12-12T11:15:00+00:00 | signin | 2.139.88.10    | signin | app=Azure Resource Manager client= status=50076 result=50076 ec=50076                                                       | 5:12 |
| 2025-12-12T15:14:00+00:00 | ual    | 2.139.88.10    | ual    | op=Consent to application workload=AzureActiveDirectory                                                                     | 1:6  |
| 2025-12-12T21:05:00+00:00 | ual    | 20.190.128.12  | ual    | op=MailItemsAccessed workload=Exchange                                                                                      | 1:16 |
| 2025-12-12T21:47:00+00:00 | signin | 5.62.41.22     | signin | app=Graph Explorer client=Other clients status=0 result=0                                                                   | 3:3  |
| 2025-12-13T04:05:00+00:00 | signin | 20.190.128.12  | signin | app=SharePoint Online client=Exchange ActiveSync status=0 result=0                                                          | 6:6  |
| 2025-12-13T15:06:00+00:00 | signin | 83.45.12.33    | signin | app=Azure Portal client=Browser status=0 result=0                                                                           | 3:19 |
| 2025-12-13T21:36:00+00:00 | signin | 83.45.12.34    | signin | app=Microsoft Teams client=Browser status=0 result=0                                                                        | 4:23 |
| 2025-12-15T10:42:00+00:00 | signin | 5.62.41.22     | signin | app=Exchange Online client=Exchange ActiveSync status=50053 result=50053 ec=50053 fr=Account is locked.                     | 6:28 |
| 2025-12-16T06:54:00+00:00 | signin | 104.26.12.88   | signin | app=Graph Explorer client=Browser status=50058 result=50058 ec=50058 fr=Account is locked.                                  | 7:2  |
| 2025-12-17T09:43:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft Teams client=Browser status=50074 result=50074 ec=50074 fr=MFA required.                                      | 7:22 |
| 2025-12-18T01:37:00+00:00 | signin | 83.45.12.33    | signin | app=Microsoft 365 Admin Center client=Browser status=50058 result=50058 ec=50058 fr=Invalid username or password.           | 3:28 |
| 2025-12-18T08:20:00+00:00 | ual    | 104.26.12.88   | ual    | op=Send workload=Exchange                                                                                                   | 1:38 |
| 2025-12-18T18:26:00+00:00 | signin | 20.190.128.12  | signin | app=SharePoint Online client=Exchange ActiveSync status=50058 result=50058 ec=50058 fr=Token issuer anomaly detected.       | 7:26 |
| 2025-12-19T19:10:00+00:00 | signin | 20.190.128.12  | signin | app=Azure Portal client=IMAP4 status=50058 result=50058 ec=50058 fr=Invalid username or password.                           | 4:4  |
| 2025-12-21T11:21:00+00:00 | signin | 83.45.12.34    | signin | app=Exchange Online client=Other clients status=50074 result=50074 ec=50074 fr=MFA required.                                | 3:13 |
| 2025-12-22T03:59:00+00:00 | ual    | 185.199.110.42 | ual    | op=Set-Mailbox workload=Exchange                                                                                            | 1:3  |
| 2025-12-22T07:46:00+00:00 | ual    | 104.26.12.88   | ual    | op=FileAccessed workload=SharePoint                                                                                         | 1:17 |
| 2025-12-23T05:16:00+00:00 | ual    | 83.45.12.33    | ual    | op=UserLoggedIn workload=AzureActiveDirectory                                                                               | 1:20 |
| 2025-12-24T21:00:00+00:00 | signin | 2.139.88.10    | signin | app=Exchange Online client=Other clients status=50076 result=50076 ec=50076 fr=Token issuer anomaly detected.               | 6:17 |
| 2025-12-25T00:30:00+00:00 | signin | 83.45.12.33    | signin | app=Microsoft Teams client=Mobile Apps and Desktop clients status=50074 result=50074 ec=50074 fr=User did not complete MFA. | 7:29 |
| 2025-12-25T04:08:00+00:00 | signin | 83.45.12.34    | signin | app=Microsoft Teams client=Browser status=0 result=0                                                                        | 6:7  |
| 2025-12-25T07:13:00+00:00 | signin | 2.139.88.10    | signin | app=SharePoint Online client=Exchange ActiveSync status=50074 result=50074 ec=50074 fr=MFA required.                        | 7:12 |
| 2025-12-25T08:11:00+00:00 | ual    | 83.45.12.34    | ual    | op=Add-MailboxPermission workload=Exchange                                                                                  | 1:37 |
| 2025-12-26T00:47:00+00:00 | ual    | 83.45.12.33    | ual    | op=New-InboxRule workload=Exchange                                                                                          | 1:25 |
| 2025-12-28T21:32:00+00:00 | signin | 185.199.110.42 | signin | app=Microsoft Teams client=Other clients status=0 result=0                                                                  | 4:14 |
| 2025-12-31T14:17:00+00:00 | ual    | 83.45.12.33    | ual    | op=Send workload=Exchange                                                                                                   | 1:19 |
| 2026-01-01T10:19:00+00:00 | signin | 83.45.12.34    | signin | app=Azure Resource Manager client= status=0 result=0                                                                        | 5:20 |
| 2026-01-02T03:48:00+00:00 | signin | 83.45.12.34    | signin | app=Graph Explorer client=Exchange ActiveSync status=0 result=0                                                             | 7:13 |
| 2026-01-03T15:01:00+00:00 | signin | 83.45.12.33    | signin | app=SharePoint Online client=IMAP4 status=50053 result=50053 ec=50053 fr=Account is locked.                                 | 3:16 |
| 2026-01-04T22:21:00+00:00 | ual    | 104.26.12.88   | ual    | op=Add member to role workload=AzureActiveDirectory                                                                         | 1:36 |