# Client application and integration governance

Una Labs does not register OAuth apps, GitHub Apps, webhooks, or long-lived access tokens merely to complete a platform checklist.

Every client integration requires:

- a named product owner and operational purpose;
- the minimum scopes and repository access;
- an approved callback and privacy boundary;
- secret storage outside source control;
- installation and access review evidence;
- credential rotation and revocation instructions;
- an owner-approved retirement date or review cadence.

GitHub Apps are preferred over broad personal access tokens when an automation genuinely requires organization access. Unused integrations must be removed rather than left dormant.
