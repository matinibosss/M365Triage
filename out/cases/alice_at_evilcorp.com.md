# Case view: alice@evilcorp.com

## Summary
- Sign-ins: success=10 fail=14 distinct_ips=7

## Recent timeline (last 200 events)
| ts                        | src    | ip             | action | detail                                                                                                                | ref  |
| ------------------------- | ------ | -------------- | ------ | --------------------------------------------------------------------------------------------------------------------- | ---- |
| 2025-12-11T12:09:00+00:00 | signin | 20.190.128.12  | signin | app=Microsoft Teams client=POP3 status=50058 result=50058 ec=50058 fr=Account is locked.                              | 6:20 |
| 2025-12-12T04:49:00+00:00 | signin | 83.45.12.34    | signin | app=SharePoint Online client=IMAP4 status=0 result=0                                                                  | 6:11 |
| 2025-12-12T21:41:00+00:00 | signin | 83.45.12.34    | signin | app=Microsoft Teams client=Mobile Apps and Desktop clients status=0 result=0                                          | 3:12 |
| 2025-12-13T21:30:00+00:00 | signin | 2.139.88.10    | signin | app=Microsoft Graph client= status=0 result=50076 ec=50076                                                            | 5:18 |
| 2025-12-14T09:52:00+00:00 | signin | 185.199.110.42 | signin | app=SharePoint Online client=POP3 status=50058 result=50058 ec=50058 fr=User did not complete MFA.                    | 3:30 |
| 2025-12-14T12:11:00+00:00 | signin | 2.139.88.10    | signin | app=Azure Portal client=Other clients status=50074 result=50074 ec=50074 fr=MFA required.                             | 6:27 |
| 2025-12-15T09:09:00+00:00 | ual    | 83.45.12.34    | ual    | op=Add-MailboxPermission workload=Exchange                                                                            | 1:24 |
| 2025-12-16T04:16:00+00:00 | signin | 20.190.128.12  | signin | app=Microsoft 365 Admin Center client=Exchange ActiveSync status=0 result=0                                           | 4:12 |
| 2025-12-16T09:52:00+00:00 | signin | 104.26.12.88   | signin | app=SharePoint Online client=Exchange ActiveSync status=50053 result=50053 ec=50053 fr=User did not complete MFA.     | 3:4  |
| 2025-12-17T04:17:00+00:00 | ual    | 83.45.12.34    | ual    | op=MailItemsAccessed workload=Exchange                                                                                | 1:4  |
| 2025-12-17T12:47:00+00:00 | ual    | 185.199.110.42 | ual    | op=Add member to role workload=AzureActiveDirectory                                                                   | 1:35 |
| 2025-12-17T23:36:00+00:00 | ual    | 5.62.41.22     | ual    | op=Send workload=Exchange                                                                                             | 1:22 |
| 2025-12-19T06:30:00+00:00 | signin | 20.190.128.12  | signin | app=Graph Explorer client=IMAP4 status=50058 result=50058 ec=50058 fr=Token issuer anomaly detected.                  | 6:21 |
| 2025-12-19T08:19:00+00:00 | signin | 83.45.12.33    | signin | app=Microsoft Teams client=IMAP4 status=50053 result=50053 ec=50053 fr=Token issuer anomaly detected.                 | 7:9  |
| 2025-12-20T23:23:00+00:00 | ual    | 185.199.110.42 | ual    | op=UserLoggedIn workload=AzureActiveDirectory                                                                         | 1:15 |
| 2025-12-21T23:32:00+00:00 | ual    | 83.45.12.33    | ual    | op=Set-Mailbox workload=Exchange                                                                                      | 1:11 |
| 2025-12-22T03:00:00+00:00 | signin | 83.45.12.33    | signin | app=Graph Explorer client=POP3 status=50074 result=50074 ec=50074 fr=Account is locked.                               | 4:11 |
| 2025-12-23T03:59:00+00:00 | signin | 5.62.41.22     | signin | app=SharePoint Online client=Exchange ActiveSync status=50058 result=50058 ec=50058 fr=Token issuer anomaly detected. | 7:10 |
| 2025-12-23T19:03:00+00:00 | signin | 83.45.12.34    | signin | app=SharePoint Online client=Other clients status=50074 result=50074 ec=50074 fr=User did not complete MFA.           | 4:19 |
| 2025-12-23T21:08:00+00:00 | signin | 83.45.12.34    | signin | app=Azure Resource Manager client= status=0 result=0                                                                  | 5:8  |
| 2025-12-24T06:24:00+00:00 | signin | 185.199.110.42 | signin | app=Exchange Online client=IMAP4 status=0 result=0                                                                    | 6:15 |
| 2025-12-24T14:59:00+00:00 | ual    | 83.45.12.34    | ual    | op=FileAccessed workload=SharePoint                                                                                   | 1:2  |
| 2025-12-25T07:03:00+00:00 | signin | 5.62.41.22     | signin | app=Azure Portal client=IMAP4 status=0 result=0                                                                       | 7:27 |
| 2025-12-25T19:44:00+00:00 | signin | 104.26.12.88   | signin | app=Azure Resource Manager client= status=50076 result=0                                                              | 5:17 |
| 2025-12-27T21:10:00+00:00 | signin | 185.199.110.42 | signin | app=Graph Explorer client=Browser status=0 result=0                                                                   | 4:27 |
| 2025-12-28T05:02:00+00:00 | signin | 185.199.110.42 | signin | app=Azure Portal client=Exchange ActiveSync status=50076 result=50076 ec=50076 fr=Token issuer anomaly detected.      | 6:18 |
| 2025-12-28T21:51:00+00:00 | signin | 2.139.88.10    | signin | app=Microsoft Teams client=Exchange ActiveSync status=0 result=0                                                      | 7:20 |
| 2025-12-29T18:52:00+00:00 | ual    | 104.26.12.88   | ual    | op=MailItemsAccessed workload=Exchange                                                                                | 1:9  |
| 2025-12-29T21:44:00+00:00 | signin | 83.45.12.34    | signin | app=Graph Explorer client=Browser status=50076 result=50076 ec=50076 fr=Invalid username or password.                 | 4:20 |
| 2025-12-31T06:10:00+00:00 | ual    | 83.45.12.34    | ual    | op=UserLoggedIn workload=AzureActiveDirectory                                                                         | 1:33 |
| 2025-12-31T07:50:00+00:00 | ual    | 104.26.12.88   | ual    | op=FileAccessed workload=SharePoint                                                                                   | 1:12 |
| 2026-01-01T08:15:00+00:00 | ual    | 5.62.41.22     | ual    | op=Send workload=Exchange                                                                                             | 1:40 |
| 2026-01-03T18:40:00+00:00 | signin | 83.45.12.34    | signin | app=Microsoft 365 Admin Center client=POP3 status=50074 result=50074 ec=50074 fr=Invalid username or password.        | 7:19 |
| 2026-01-04T03:10:00+00:00 | signin | 185.199.110.42 | signin | app=Exchange Online client=POP3 status=0 result=0                                                                     | 3:18 |
| 2026-01-04T07:24:00+00:00 | ual    | 5.62.41.22     | ual    | op=Set-Mailbox workload=Exchange                                                                                      | 1:18 |
| 2026-01-04T17:58:00+00:00 | ual    | 2.139.88.10    | ual    | op=Add-MailboxPermission workload=Exchange                                                                            | 1:31 |
| 2026-01-04T20:57:00+00:00 | signin | 83.45.12.34    | signin | app=Microsoft 365 Admin Center client=POP3 status=50074 result=50074 ec=50074 fr=Account is locked.                   | 7:17 |