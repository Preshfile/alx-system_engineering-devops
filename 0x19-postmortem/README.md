POSTMOTERM ON OUR SUPPORTBOT SYSTEM
Issue Summary:
Duration: The outage lasted from March 1st, 2023 at 2:00 PM UTC to March 2nd, 2023 at 9:00 AM UTC.
Impact: The web assistant was completely down during the outage, resulting in users being unable to use both the chatbot and voice assistant components. Approximately 75% of users were affected.
Root cause: The root cause of the outage was a software bug in the Node.js server that caused it to crash and become unresponsive.
Timeline:
2:00 PM UTC: The issue was first detected when monitoring alerts signaled that the server was unresponsive.
2:05 PM UTC: An engineer was alerted and began investigating the issue.
2:15 PM UTC: The engineer determined that the server was down and began investigating potential causes.
2:30 PM UTC: The engineer assumed the issue was related to a network outage and began investigating network connectivity.
3:00 PM UTC: The engineer determined that the issue was not related to network connectivity and shifted focus to the Node.js server.
4:00 PM UTC: The engineer discovered the software bug that was causing the server to crash and began working on a fix.
9:00 PM UTC: The engineer completed the fix and tested it in a staging environment.
10:00 PM UTC: The engineer deployed the fix to the production environment and began monitoring the server.
9:00 AM UTC: The engineer confirmed that the fix was successful and closed the incident.
Misleading investigation/debugging paths that were taken: The engineer initially assumed that the issue was related to network connectivity and spent time investigating that before realizing it was a software issue with the server.
Escalation: The incident was escalated to the development team responsible for the Node.js server.

Resolution:
Root cause: The root cause of the issue was a software bug in the Node.js server that caused it to crash and become unresponsive.
Resolution: The issue was resolved by fixing the software bug in the Node.js server.
Corrective and preventative measures:
To prevent similar incidents in the future, the following measures will be taken:
•	The Node.js server will be updated to the latest stable version to ensure that any known issues are addressed.
•	The monitoring system will be improved to provide more detailed alerts and enable quicker detection of issues.
•	The development team will review their development practices to identify potential areas for improvement to prevent similar bugs from being introduced in the future.
Specific tasks to address the issue include:
•	Updating the Node.js server to the latest stable version.
•	Improving the monitoring system to provide more detailed alerts.
•	Reviewing the development practices to identify potential areas for improvement.


