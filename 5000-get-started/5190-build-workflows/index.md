﻿[title]: # (Build Workflow Templates)
[tags]: # (Account Lifecycle Manager,ALM,)
[priority]: # (5190)

# Build Workflow Templates

To use ALM, you must define the approval processes your organization intends to apply to requests for different kinds of service accounts. Some types of service accounts might be approved and provisioned on request, while others might need more than one approval before provisioning.

## Overview

ALM supplies a straightforward, roles-driven workflow system to support your oversight of new AD account creation, review, and eventual renewal or retirement.

ALM represents your approval processes as Workflow Templates. Each template defines the approval process for a particular service account kind or category as defined by your organization—for example, service accounts belonging to specific Active Directory groups.

## Built-In Roles

ALM’s workflow system relies on three built-in User Roles:

* A **System Administrator** sets up the Workflow Templates that define the approval processes for users belonging to specific Active Directory groups, or to any of a set of Active Directory groups.

* A **Requester** uses ALM to ask for a service account to be set up in Active Directory. The Active Directory group requested for the account determines which Workflow Template the Requester will use to request the account. The template determines the approval steps and the specific approvers.

* An **Approver** uses ALM to approve (or deny) service account requests.
 
## Workflow Process

As illustrated, ALM’s workflow system follows a simple, linear process from template d

![Workflow Process](workflow-process.png)

# Create a Workflow Template to Define a Workflow

You must have the System Administrator role to perform this procedure, and you must have already connected ALM to your Secret Server.

Use this procedure to create the Workflow Templates necessary to support your organization’s use cases:

* In the left-side main menu, select the **Workflow Templates** page.

* Use the **Create Template** button (upper right of the page) to open the **Add Workflow Template** panel.

* Supply a name for the template.

* Select the **Account Type**.

* Supply the **Terms of Service**.

* Define the **Purpose** of the Workflow Template.

* Set up the **Active Directory**.

* Connect the **Secrets Vault**.

* Choose the **End of Lifecycle Action** for accounts based on this template:

  * Review, Disable, Expire, or Delete

* Define the **Review Intervals** available to the Requester.

* Choose **Notification Options**:

  * Before End of Lifecycle Notifications

  * On/After End of Lifecycle Notifications

* Define the **Approval Steps**.

* Add **Approvers** to at least one Approval Step. You can add individual Users, or Groups thereof.

* Publish the completed Workflow Template.

![Article End](../../alm-bug.png)

  

  