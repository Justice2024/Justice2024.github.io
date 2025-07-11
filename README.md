# guide/process on weekly routine task

1\. Audit & Sign-in Logs Review (Microsoft Entra)&#x20;

Purpose: \
Identify unauthorized access, unfamiliar users, or anomalous sign-in behavior.&#x20;

Steps:&#x20;

1. Sign in to [Microsoft Entra Admin Center](https://entra.microsoft.com/).&#x20;
2. Navigate to: Monitoring & Health > Sign-in Logs.&#x20;
3. Filter logs for:&#x20;

* Status (success, failure, interrupted)&#x20;
* Last 7/30 days (as applicable).&#x20;
* Unsuccessful sign-ins, unfamiliar locations, or users with high-risk sign-ins.&#x20;

4. Review each entry for:&#x20;

* Unrecognized usernames or GUIDs.&#x20;
* Suspicious IP addresses or locations.&#x20;
* Application sign-in anomalies.&#x20;

Documentation Template:&#x20;

* Date of Review&#x20;
* Outcome: Brief summary of findings.&#x20;
* Actions Taken:&#x20;
* IDs retrieved: Resource ID, Resource Tenant ID, Home Tenant ID.&#x20;
* IP address logged.&#x20;
* User identified (if applicable).&#x20;
* Update: (e.g., “User confirmed as internal/external; investigation ongoing/resolved.”)&#x20;
* Recommendation: Escalate or no action required.&#x20;

![Shape](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAANSURBVBhXY2BgYGAAAAAFAAGKM+MAAAAAAElFTkSuQmCC)&#x20;

![Shape](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAANSURBVBhXY2BgYGAAAAAFAAGKM+MAAAAAAElFTkSuQmCC)&#x20;

✅ 2. Microsoft 365 Defender Security Review&#x20;

Purpose: \
Ensure no active threats, risky users, or anomalies in the Microsoft 365 environment.&#x20;

Steps:&#x20;

1. Sign in to [Microsoft 365 Defender Portal](https://security.microsoft.com/).&#x20;
2. Navigate to:&#x20;

* Incidents & Alerts&#x20;
* Users > Risky Users&#x20;
* Audit Logs&#x20;

3. Check for:&#x20;

* Risky users (flagged by Microsoft).&#x20;
* Open incidents or triggered alerts.&#x20;
* Audit logs showing abnormal activities (e.g., mailbox permission changes, elevated privileges).&#x20;

Documentation Template:&#x20;

* Date of Review&#x20;
* Risky Users: List if any.&#x20;
* Alerts/Incidents: Detail alerts found (if any).&#x20;
* Actions Taken: Audit logs reviewed, unusual behavior tracked.&#x20;
* Conclusion: (e.g., “System stable; no active threats.”)&#x20;
* Recommendation: N/A or mitigation actions if needed.&#x20;
