#  Server Dumps

 This repository contains logs extracted from the corporate servers.

## Files

- **system_events.log**  
  Time-stamped records of server activity. Look for unusual actions, file deletions, or system alerts.

- **vault_access.log**  
  Shows who attempted to access the treasury system. Only certain users or systems are authorized. Pay attention to successful and denied attempts.

- **user_activity.json**  
  High-level summary of user logins and sessions across TechSphere. Compare this with other logs to detect anomalies or suspicious activity.


## Guidance

1. Compare timestamps across the logs to find correlations between events.  
2. Identify which systems/users have legitimate access and which attempts were denied.  
3. Look for anomalies — any action that seems out of sequence or unexpected may indicate unauthorized activity.  

