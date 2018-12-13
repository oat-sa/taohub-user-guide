<!--
created_at: 2016-12-15
authors:         
    - "Catherine Pease"
--> 

# User Management

>User Management in TAO involves adding and editing user profiles, assigning roles to specific users, and granting users access rights to specific areas of TAO.
 

These user-related functions, which are accessible to [Global Managers](../appendix/glossary.md#global-manager) or [Tenant Administrators](../appendix/glossary.md#tenant-administrator), are organized in four functional tabs: 

- **Manage Users**
- **Add A User**
- **Manage Roles**
- **Manage Access Rights**. 


All User Management functions can be found under the Users icon (depicted with two heads), located on the right-hand side of the [Assessment Builder Bar](../appendix/glossary.md#assessment-builder_bar). 

*Note: Roles differ slightly in TAO depending on the edition you are using. In the Premium Edition, the tenant administrator can manage and add users, and assign roles to them, but cannot manage roles (define or modify them) or access rights. In the Community Edition, the global manager acts as the main administrator, and can carry out all of the four functions named above.*

**1.** Adding a new user

This tab allows new User accounts to be created on your TAO system. These can include any user from an administrator to a [Test-taker](../appendix/glossary.md#test-taker).

Click on the *Add a user* tab. Fill in the following fields in the panel that appears in the canvas area: 

- **Label** (full name or easy-to-remember nickname)
- **Data Language** (language used by administrators)
- **Interface Language** (language used by the user)
- **Login** (must be unique, cannot be changed once set)
- **Roles** (as desired) 
- **Password and Repeat Password** (to be given to the user). 
 
The *First Name*, *Last Name*, and *Mail* (E-mail) fields are optional.

![Adding a new User](../resources/backend/users/add-a-user.png)

**2.** Managing users

This tab provides an overview of all the users registered in your TAO system. Included are administrators and test-takers, and any other roles assigned to the accounts of individuals to whom you have granted access.

To edit these, click on the *Manage Users* tab. Find the profile that you wish to edit. Review the information in the table, and then click the *Edit* button. You can edit any of the data in the panel which appears.

*Note: It is not possible to change the login of an existing user. If there is a login conflict, it will need to be resolved without editing this field.*

This is the procedure used for such actions as changing passwords, e-mail contact information, etc. Alternatively, this is also the tab to use to remove profiles, which you can do by clicking on the appropriate button on the right of the canvas.

**3.** Managing roles

This tab can be used to assign roles to specific users. 

To do this, select *Manage roles*. In the canvas which appears there will be two panels sitting side-by-side. The left panel shows the tree of roles with classes (folders). The right panel is by default empty. In the left panel, select either a single role. These will have a label, and the roles assigned to this label can be edited in this window. You can create your own role (by clicking *New Role*) and select which roles you want to be included by ticking the check boxes next to the  role, or combination of roles which are to be assigned to the individual(s). 

See the section on [Roles and Permissions](../administrative-features/roles-and-permissions.md) for a comprehensive list of the roles available.

Select the users who will be assigned to this role by clicking on the *Assign users* button in the [Action Bar](../appendix/glossary.md#action-bar). A list of TAO users will appear. Select the check boxes of the users to whom you wish to assign this role. When all the desired users are selected, click *Save*.


**4.** Managing access rights.

This tab provides the means for changing the access rights of roles within your TAO system. Access to modules can be changed in this tab, by either adding or removing them from a specific role.

To customize or edit access rights for different roles, click on the *Manage Access Rights* tab. In the menu which appears in the first column in the canvas area, select the role you wish to modify. Review the *Modules* list in the second column. Check the appropriate boxes for those modules you want the role to access (or uncheck those boxes you no longer want the role to access). 
