# Centralized Log Collection & Monitoring

## Objective
To collect and analyze Linux authentication logs using Splunk SIEM in order to detect suspicious login activity.

## Environment
- Ubuntu Linux (Log Source)
- Splunk SIEM
- VirtualBox

## Log Sources
- /var/log/auth.log
- /var/log/syslog

## Steps Performed
1. Installed and configured Splunk SIEM on Ubuntu
2. Added Linux authentication and system logs as data inputs
3. Generated failed SSH login attempts
4. Analyzed raw log events using Splunk Search
5. Aggregated failed login attempts to identify suspicious patterns

## Detection Use Case
- SSH failed login attempts (potential brute-force activity)

## Outcome
Successfully detected and analyzed failed SSH login attempts using Splunk SIEM.

## Screenshots
Splunk Dashboard:-
![Splunk Dashboard](Screenshots/01_Splunk_dashboard.png)
Log Inputs:-
![Log Inputs](Screenshots/02_log_inputs.png)
Failed Login Events:-
![Failed Login Events](Screenshots/03_failed_login_events.png)
Aggregated Failed Login:-
![Aggregated Failed Logins](Screenshots/04_failed_login_stats.png)

