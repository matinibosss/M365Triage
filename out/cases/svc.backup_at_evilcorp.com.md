# Case view: svc.backup@evilcorp.com

## Summary
- Sign-ins: success=8 fail=14 distinct_ips=6

## Recent timeline (last 200 events)
| ts                        | src    | ip             | action | detail                                                                                                                         | ref  |
| ------------------------- | ------ | -------------- | ------ | ------------------------------------------------------------------------------------------------------------------------------ | ---- |
| 2025-12-12T02:32:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft Teams client=Other clients status=50074 result=50074 ec=50074 fr=Token issuer anomaly detected.                  | 6:4  |
| 2025-12-12T05:53:00+00:00 | signin | 20.190.128.12  | signin | app=Microsoft 365 Admin Center client=Browser status=50076 result=50076 ec=50076 fr=Token issuer anomaly detected.             | 7:1  |
| 2025-12-13T09:30:00+00:00 | signin | 20.190.128.12  | signin | app=Azure Resource Manager client= status=0 result=0                                                                           | 5:10 |
| 2025-12-13T21:30:00+00:00 | ual    | 20.190.128.12  | ual    | op=Add service principal workload=AzureActiveDirectory                                                                         | 1:5  |
| 2025-12-14T19:05:00+00:00 | ual    | 83.45.12.33    | ual    | op=Consent to application workload=AzureActiveDirectory                                                                        | 1:7  |
| 2025-12-15T04:02:00+00:00 | signin | 83.45.12.34    | signin | app=Graph Explorer client=Browser status=50074 result=50074 ec=50074 fr=Account is locked.                                     | 3:11 |
| 2025-12-18T06:53:00+00:00 | signin | 20.190.128.12  | signin | app=Azure Resource Manager client= status=0 result=50076 ec=50076                                                              | 5:13 |
| 2025-12-18T14:47:00+00:00 | ual    | 83.45.12.33    | ual    | op=FileDownloaded workload=SharePoint                                                                                          | 1:13 |
| 2025-12-18T19:04:00+00:00 | signin | 104.26.12.88   | signin | app=Azure Portal client=Browser status=0 result=0                                                                              | 7:21 |
| 2025-12-19T04:43:00+00:00 | signin | 5.62.41.22     | signin | app=Graph Explorer client=Exchange ActiveSync status=50058 result=50058 ec=50058 fr=Invalid username or password.              | 4:10 |
| 2025-12-20T10:29:00+00:00 | ual    | 2.139.88.10    | ual    | op=Add member to role workload=AzureActiveDirectory                                                                            | 1:39 |
| 2025-12-20T17:48:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft 365 Admin Center client=POP3 status=50053 result=50053 ec=50053 fr=User did not complete MFA.                    | 4:8  |
| 2025-12-22T23:31:00+00:00 | ual    | 20.190.128.12  | ual    | op=SharingSet workload=SharePoint                                                                                              | 1:14 |
| 2025-12-23T00:59:00+00:00 | signin | 185.199.110.42 | signin | app=Microsoft Teams client=Browser status=50058 result=50058 ec=50058 fr=MFA required.                                         | 6:5  |
| 2025-12-23T11:39:00+00:00 | signin | 104.26.12.88   | signin | app=Azure Portal client=Mobile Apps and Desktop clients status=0 result=0                                                      | 7:15 |
| 2025-12-23T15:16:00+00:00 | signin | 185.199.110.42 | signin | app=Azure Portal client=Exchange ActiveSync status=0 result=0                                                                  | 3:9  |
| 2025-12-24T03:36:00+00:00 | signin | 2.139.88.10    | signin | app=Graph Explorer client=Exchange ActiveSync status=0 result=0                                                                | 6:12 |
| 2025-12-24T03:59:00+00:00 | signin | 83.45.12.34    | signin | app=Exchange Online client=Other clients status=0 result=0                                                                     | 6:1  |
| 2025-12-24T08:36:00+00:00 | signin | 83.45.12.34    | signin | app=Azure Resource Manager client= status=0 result=50076 ec=50076                                                              | 5:9  |
| 2025-12-25T11:26:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft Graph client= status=0 result=0                                                                                  | 5:4  |
| 2025-12-25T20:48:00+00:00 | signin | 20.190.128.12  | signin | app=Graph Explorer client=Other clients status=50058 result=50058 ec=50058 fr=MFA required.                                    | 3:10 |
| 2025-12-25T22:41:00+00:00 | signin | 83.45.12.34    | signin | app=Microsoft 365 Admin Center client=Mobile Apps and Desktop clients status=50076 result=50076 ec=50076 fr=Account is locked. | 3:29 |
| 2025-12-26T03:16:00+00:00 | signin | 5.62.41.22     | signin | app=Microsoft Teams client=Mobile Apps and Desktop clients status=50076 result=50076 ec=50076 fr=User did not complete MFA.    | 3:6  |
| 2025-12-30T00:35:00+00:00 | ual    | 83.45.12.33    | ual    | op=Add service principal workload=AzureActiveDirectory                                                                         | 1:29 |
| 2025-12-30T14:53:00+00:00 | signin | 185.199.110.42 | signin | app=Graph Explorer client=Browser status=50053 result=50053 ec=50053 fr=Account is locked.                                     | 3:1  |
| 2026-01-01T18:23:00+00:00 | signin | 5.62.41.22     | signin | app=Azure Portal client=Mobile Apps and Desktop clients status=50076 result=50076 ec=50076 fr=User did not complete MFA.       | 3:5  |
| 2026-01-02T08:59:00+00:00 | signin | 83.45.12.34    | signin | app=Microsoft Graph client= status=50076 result=0                                                                              | 5:11 |
| 2026-01-03T07:05:00+00:00 | ual    | 104.26.12.88   | ual    | op=UserLoggedIn workload=AzureActiveDirectory                                                                                  | 1:34 |
| 2026-01-04T18:26:00+00:00 | signin | 2.139.88.10    | signin | app=SharePoint Online client=Exchange ActiveSync status=50074 result=50074 ec=50074 fr=Invalid username or password.           | 4:6  |