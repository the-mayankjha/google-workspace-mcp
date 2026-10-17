# Google Workspace MCP v1.1.2

- Fix Google Tasks create/list API paths.
- Report Calendar, Tasks and Drive errors instead of returning misleading empty lists.
- Honor completed-task and calendar-start filters.
- Validate meeting timestamps and timezones; derive a missing end time safely.
- Return only real Google Meet links; never fabricate a link.
