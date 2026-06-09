# AAP 2.6 Demo Repository

Demo-Playbooks für die Ansible Automation Platform 2.6 Präsentation.

## Use Cases

| # | Name | AAP-Feature |
|---|------|-------------|
| 1 | System Health Check | Surveys, Fact Cache |
| 2 | User Management | Surveys (Dropdown + Text), become |
| 3 | Webserver Setup | Jinja2-Templates, Service Handling |
| 4 | Security Hardening | Check Mode, Diff Mode, Tags |
| 5 | Deployment Workflow | Workflow Job Templates, On-Failure Rollback |

## Inventory

Alle Playbooks laufen auf `localhost` (ansible_connection: local).

## Struktur

```
playbooks/
  01_system_health_check.yml
  02_user_management.yml
  03_webserver_setup.yml
  04_security_hardening.yml
  05_pre_flight_check.yml
  05_deploy.yml
  05_smoke_test.yml
  05_rollback.yml
templates/
  index.html.j2
  sshd_config.j2
```
