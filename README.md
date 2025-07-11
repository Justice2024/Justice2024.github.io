# guide/process on weekly routine task
1. Audit & Sign-in Logs Review (Microsoft Entra)
Purpose:
Identify unauthorized access, unfamiliar users, or anomalous sign-in behavior.
Steps:
Sign in to Microsoft Entra Admin Center.
Navigate to: Monitoring & Health > Sign-in Logs.
Filter logs for:
Status (success, failure, interrupted)
Last 7/30 days (as applicable).
Unsuccessful sign-ins, unfamiliar locations, or users with high-risk sign-ins.
Review each entry for:
Unrecognized usernames or GUIDs.
Suspicious IP addresses or locations.
Application sign-in anomalies.


Documentation Template:

* Date of Review
* Outcome: Brief summary of findings.
* Actions Taken:
* IDs retrieved: Resource ID, Resource Tenant ID, Home Tenant ID.
* IP address logged.
* User identified (if applicable).
* Update: (e.g., “User confirmed as internal/external; investigation ongoing/resolved.”)
* Recommendation: Escalate or no action required.

![Shape](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAANSURBVBhXY2BgYGAAAAAFAAGKM+MAAAAAAElFTkSuQmCC)

![Shape](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAANSURBVBhXY2BgYGAAAAAFAAGKM+MAAAAAAElFTkSuQmCC)

✅ 2. Microsoft 365 Defender Security Review

Purpose:\
Ensure no active threats, risky users, or anomalies in the Microsoft 365 environment.

Steps:

1. Sign in to [Microsoft 365 Defender Portal](https://security.microsoft.com/).
2. Navigate to:

* Incidents & Alerts
* Users > Risky Users
* Audit Logs

3. Check for:

* Risky users (flagged by Microsoft).
* Open incidents or triggered alerts.
* Audit logs showing abnormal activities (e.g., mailbox permission changes, elevated privileges).

Documentation Template:

* Date of Review
* Risky Users: List if any.
* Alerts/Incidents: Detail alerts found (if any).
* Actions Taken: Audit logs reviewed, unusual behavior tracked.
* Conclusion: (e.g., “System stable; no active threats.”)
* Recommendation: N/A or mitigation actions if needed.
