# Change Management Policy

- Owner:    David Benson
- Company:    JGraph Ltd
- Version:    1.1
- Published:    29 November 2018
- Status:        Published

### Background Information

JGraph Ltd is an open source technology stack for building diagramming applications, and the world’s most widely used browser-based end-user diagramming application draw.io.
JGraph Ltd aims to provide free, high quality diagramming software for everyone.

### Purpose

This policy defines the requirements for managing changes within JGraph Ltd systems.

### Scope

This policy applies to all personnel, including contractors, of JGraph Ltd and all activities relating to the use, handling, management or control of information assets and systems controlled by JGraph Ltd.

### Change Management

Change management is required to ensure significant changes made to software are recorded, formally control production releases, maintain an audit trail, provide operational consistency and deliver a source of truth to recover systems in a severe event.

As part of change management, JGraph Ltd will:

- Prepare and plan the change to include implementation steps, design, schedule, test, rollback and communication plans.
- Evaluate and review changes and verify preparation and planning is complete and suitable. Changes must not introduce undue risk.
- Authorised reviewers will approve or reject the change based on the presented plans and evaluation outcome.
- Communicate changes to stakeholders and impacted parties where possible.
- Implement the change as detailed within the plans, and validate the change has been successful.
- Document the change and any commentary obtained through the review, and if the change was approved or rejected.
- Post-Change Review to validate the change is performing as expected.

### Source Control

All source code developed will be held within a GIT repository and on multiple physically separate systems.

### Release Management

Releases will be maintained between main/master, release and development branches. Development branches are merged into the release branch prior to release.

Commits to the release branch are restricted to administrators.

### Reproducibility

Every product release must be reproducible to allow for targeted bug fixes to be deployed without needing to introduce additional and unrequired system changes.
