# FirstSolution
User Story: Automate Secret Sharing Permissions via Folder Events in Delinea Secret Server
As a Delinea Secret Server Administrator,
I want to configure an event pipeline for secrets placed within a specific folder,
so that designated users or groups automatically gain access or are notified, ensuring efficient and controlled secret distribution.

Acceptance Criteria:
Pipeline Configuration: The Secret Server Administrator shall be able to create a new event pipeline that specifies a target secret folder as the trigger scope.
Trigger Event Selection: The pipeline configuration must allow selection of the triggering event type, such as 'Secret Created' or 'Secret Moved Into Folder' within the specified folder.
Automated Permission Assignment: The pipeline shall enable the administrator to define which Delinea Secret Server users or groups automatically gain 'View' or 'Edit' (configurable) permissions to any secret placed within the configured target folder.
Successful Execution: Upon a secret being created or moved into the specified target folder, the configured permissions shall be automatically applied to that secret for the designated users/groups without manual intervention.
Auditable Logging: All successful and failed executions of the event pipeline (i.e., secret events and permission assignments) must be recorded in the Delinea Secret Server audit logs for traceability and troubleshooting.
