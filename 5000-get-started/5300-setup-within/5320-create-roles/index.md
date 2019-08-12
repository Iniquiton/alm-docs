﻿[title]: # (Create Roles)
[tags]: # (Account Lifecycle Manager,ALM,)
[priority]: # (5320)

### Create Roles

**Roles** control privileges within ALM, and **only within ALM**.

* Like ALM groups, ALM roles do **not** correspond to any similar entities in Active Directory or any other directory system.

Role names often reference job titles, but astute ALM administrators will name ALM roles to suggest the **privileges** the role confers in ALM, not to describe the role’s **duties**.

* To create new roles, go to **Roles \> Create Role**.

* Enter a name for the new role.

* **Add** the new role to ALM.

ALM supplies several default roles, as in the following table, that your organization may find adequate or may use as models for its own roles development.
  
----
  
| Default ALM Role     | Permissions                                      | 
|----------------------|--------------------------------------------------|
| Provision Requester  | request a new account                            |
| Provision Approver   | approve requests                                 |
| System Administrator | authorize all role types                         |
|                      | create workflow templates                        |
|                      | set up remote workers                            |
|                      | perform ALM integration with Active Directory    |
|                      | perform ALM integration with Secret Server       |
| Workflow Manager     | approve workflows                                |
|                      | set up workflow approval steps                   |                                                                                                              
  
----
  
#### Define Role Permissions

After you add a new role, ALM displays the **Details and Permissions** panel, which features controls used to define or adjust permissions for the role.

* Adjust the permissions by clicking any of the CREATE, READ, UPDATE, DELETE, or MANAGE toggle boxes for each of the features.

* Unchecking one of the permissions check boxes **for a feature** will remove from **this role** the permission to perform **that type of activity** in relation to **that feature**.

* ALM saves changes to role permissions **as you make them**—there is no save or apply button.

Continue creating roles and defining their permissions until you have satisfied the requirements for your organization’s ALM use cases.

