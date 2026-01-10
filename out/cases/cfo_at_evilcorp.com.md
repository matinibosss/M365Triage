# Case view: cfo@evilcorp.com

## Summary
- Sign-ins: success=17 fail=20 distinct_ips=7

## Recent timeline (last 200 events)
| ts                        | src    | ip             | action | detail                                                                                                                           | ref  |
| ------------------------- | ------ | -------------- | ------ | -------------------------------------------------------------------------------------------------------------------------------- | ---- |
| 2025-12-11T15:19:00+00:00 | signin | 185.199.110.42 | signin | app=Exchange Online client=IMAP4 status=0 result=0                                                                               | 4:9  |
| 2025-12-11T18:24:00+00:00 | signin | 185.199.110.42 | signin | app=Exchange Online client=Exchange ActiveSync status=50074 result=50074 ec=50074 fr=Account is locked.                          | 6:19 |
| 2025-12-12T00:03:00+00:00 | signin | 104.26.12.88   | signin | app=Azure Portal client=Exchange ActiveSync status=50053 result=50053 ec=50053 fr=Token issuer anomaly detected.                 | 4:7  |
| 2025-12-12T04:01:00+00:00 | signin | 20.190.128.12  | signin | app=Microsoft Graph client= status=50076 result=0                                                                                | 5:1  |
| 2025-12-12T17:02:00+00:00 | signin | 5.62.41.22     | signin | app=Azure Portal client=Exchange ActiveSync status=0 result=0                                                                    | 7:6  |
| 2025-12-13T18:42:00+00:00 | signin | 83.45.12.34    | signin | app=Microsoft 365 Admin Center client=Other clients status=0 result=0                                                            | 6:2  |
| 2025-12-13T21:02:00+00:00 | signin | 83.45.12.34    | signin | app=Microsoft Graph client= status=50076 result=50076 ec=50076                                                                   | 5:7  |
| 2025-12-14T10:53:00+00:00 | signin | 2.139.88.10    | signin | app=Microsoft Teams client=Browser status=50053 result=50053 ec=50053 fr=Invalid username or password.                           | 6:10 |
| 2025-12-14T14:07:00+00:00 | signin | 5.62.41.22     | signin | app=SharePoint Online client=Browser status=50058 result=50058 ec=50058 fr=MFA required.                                         | 3:7  |
| 2025-12-15T13:33:00+00:00 | ual    | 83.45.12.33    | ual    | op=UserLoggedIn workload=AzureActiveDirectory                                                                                    | 1:8  |
| 2025-12-16T20:04:00+00:00 | signin | 83.45.12.34    | signin | app=SharePoint Online client=Exchange ActiveSync status=0 result=0                                                               | 4:3  |
| 2025-12-18T04:37:00+00:00 | ual    | 104.26.12.88   | ual    | op=MailItemsAccessed workload=Exchange                                                                                           | 1:21 |
| 2025-12-18T08:10:00+00:00 | signin | 5.62.41.22     | signin | app=Azure Portal client=Other clients status=0 result=0                                                                          | 4:2  |
| 2025-12-18T13:47:00+00:00 | ual    | 185.199.110.42 | ual    | op=FileAccessed workload=SharePoint                                                                                              | 1:26 |
| 2025-12-18T15:58:00+00:00 | ual    | 5.62.41.22     | ual    | op=Send workload=Exchange                                                                                                        | 1:32 |
| 2025-12-19T06:19:00+00:00 | signin | 104.26.12.88   | signin | app=Microsoft Graph client= status=0 result=0                                                                                    | 5:6  |
| 2025-12-19T18:48:00+00:00 | signin | 20.190.128.12  | signin | app=SharePoint Online client=Browser status=50053 result=50053 ec=50053 fr=MFA required.                                         | 3:22 |
| 2025-12-20T10:32:00+00:00 | signin | 185.199.110.42 | signin | app=SharePoint Online client=Other clients status=0 result=0                                                                     | 3:24 |
| 2025-12-20T15:55:00+00:00 | signin | 83.45.12.33    | signin | app=Azure Portal client=Other clients status=0 result=0                                                                          | 4:29 |
| 2025-12-21T00:41:00+00:00 | signin | 185.199.110.42 | signin | app=Microsoft 365 Admin Center client=Other clients status=0 result=0                                                            | 7:7  |
| 2025-12-21T16:01:00+00:00 | signin | 20.190.128.12  | signin | app=SharePoint Online client=POP3 status=50076 result=50076 ec=50076 fr=MFA required.                                            | 4:5  |
| 2025-12-22T03:34:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft Teams client=Browser status=0 result=0                                                                             | 4:13 |
| 2025-12-24T01:17:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft 365 Admin Center client=Mobile Apps and Desktop clients status=0 result=0                                          | 4:28 |
| 2025-12-24T18:26:00+00:00 | signin | 2.139.88.10    | signin | app=Azure Portal client=POP3 status=50074 result=50074 ec=50074 fr=MFA required.                                                 | 6:3  |
| 2025-12-25T09:56:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft 365 Admin Center client=Browser status=0 result=0                                                                  | 6:22 |
| 2025-12-25T10:17:00+00:00 | signin | 20.190.128.12  | signin | app=Graph Explorer client=POP3 status=50053 result=50053 ec=50053 fr=User did not complete MFA.                                  | 3:26 |
| 2025-12-26T05:46:00+00:00 | signin | 104.26.12.88   | signin | app=Microsoft 365 Admin Center client=Mobile Apps and Desktop clients status=50076 result=50076 ec=50076 fr=Account is locked.   | 7:24 |
| 2025-12-27T01:34:00+00:00 | signin | 20.190.128.12  | signin | app=Microsoft Teams client=Browser status=50053 result=50053 ec=50053 fr=Account is locked.                                      | 3:2  |
| 2025-12-27T10:41:00+00:00 | signin | 83.45.12.34    | signin | app=Exchange Online client=Browser status=50074 result=50074 ec=50074 fr=Invalid username or password.                           | 4:15 |
| 2025-12-27T21:05:00+00:00 | signin | 83.45.12.33    | signin | app=SharePoint Online client=Mobile Apps and Desktop clients status=50053 result=50053 ec=50053 fr=Invalid username or password. | 4:25 |
| 2025-12-28T02:12:00+00:00 | ual    | 104.26.12.88   | ual    | op=Add-MailboxPermission workload=Exchange                                                                                       | 1:28 |
| 2025-12-29T02:40:00+00:00 | signin | 20.190.128.12  | signin | app=Exchange Online client=Exchange ActiveSync status=50076 result=50076 ec=50076 fr=Token issuer anomaly detected.              | 3:23 |
| 2025-12-29T11:35:00+00:00 | signin | 83.45.12.34    | signin | app=Graph Explorer client=Browser status=0 result=0                                                                              | 4:30 |
| 2025-12-30T01:09:00+00:00 | signin | 2.139.88.10    | signin | app=Microsoft Teams client=Mobile Apps and Desktop clients status=50076 result=50076 ec=50076 fr=MFA required.                   | 6:14 |
| 2025-12-31T05:34:00+00:00 | signin | 83.45.12.33    | signin | app=Graph Explorer client=Browser status=50074 result=50074 ec=50074 fr=Invalid username or password.                            | 3:15 |
| 2025-12-31T15:18:00+00:00 | signin | 104.26.12.88   | signin | app=Microsoft Teams client=IMAP4 status=0 result=0                                                                               | 6:9  |
| 2025-12-31T17:32:00+00:00 | signin | 83.45.12.33    | signin | app=Graph Explorer client=Mobile Apps and Desktop clients status=50058 result=50058 ec=50058 fr=Invalid username or password.    | 6:24 |
| 2025-12-31T23:38:00+00:00 | signin | 83.45.12.33    | signin | app=Microsoft 365 Admin Center client=Exchange ActiveSync status=50053 result=50053 ec=50053 fr=MFA required.                    | 7:25 |
| 2026-01-01T16:36:00+00:00 | signin | 20.190.128.12  | signin | app=Azure Resource Manager client= status=0 result=50076 ec=50076                                                                | 5:15 |
| 2026-01-02T18:00:00+00:00 | signin | 104.26.12.88   | signin | app=Microsoft Graph client= status=0 result=0                                                                                    | 5:19 |
| 2026-01-02T18:28:00+00:00 | signin | 104.26.12.88   | signin | app=SharePoint Online client=Other clients status=50074 result=50074 ec=50074 fr=User did not complete MFA.                      | 7:30 |
| 2026-01-04T19:10:00+00:00 | signin | 2.139.88.10    | signin | app=Microsoft Teams client=Browser status=0 result=0                                                                             | 7:23 |