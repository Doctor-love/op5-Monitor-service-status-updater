op5-Monitor-service-status-updater
==================================

A Python script that updates the staus of a service in op5 Monitor via the HTTP API

Usage
=====

```
./update-status.py --monhost "monitor.example.com" --username "api_user" --password "god" --host "Mail server" --service "Database backup" --status "CRITICAL" --servicemsg "Failed to dump message table"
```
