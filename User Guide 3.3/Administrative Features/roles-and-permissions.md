<!--
created_at: 2018-11-05
authors:         
    - "Catherine Pease"
--> 

# User Roles


>TAO distinguishes the following three different types of role:
>
>**Functional:** A role which can be assigned on its own to a specific user. It does not need any other role to function properly.
>
>**Additional:** A role which can be added to a specific user, in addition to already existing functional roles. These roles do not normally function on their own.
>
>**Technical:** A role which is used for technical purposes only, e.g. the use of APIs. These roles have no value to an end-user, and would be carried out by a machine, for example an authoring server connecting to TAO to publish [Tests](../appendix/glossary.md#test).



## Administrative Roles

**Tenant Administrator/Global Manager:** This functional role allows full access to a TAO tenant. This account (Tenant Administrator for the Premium Edition and Global Manager for the Community Edition) is provided to clients; the tenant administrator (or global manager) can create others from there. 

*Note: Roles differ slightly in TAO depending on the edition you are using. In the Premium Edition, the tenant administrator can manage and add users, and assign roles to them, but cannot manage roles (define or modify them) or access rights. In the Community Edition, the global manager acts as the main administrator, and is also permitted to manage roles and access rights.*


**Data Access Administator:** This additional role allows Data Access Controls to be overridden, e.g. if a certain user is locked out of a certain group of [Items](../appendix/glossary.md#item). *Note: Typically, the tenant administrator would assign this role to him or herself.*

**Operational Administrator:** This additional role allows access to Assessment Activity page, providing an overview of all ongoing test [Deliveries](../appendix/glossary.md#delivery). *Note: Typically, the tenant administrator would assign this role to him or herself. If this is the only role granted, it is necessary to bypass the welcome screen by selecting any functionality, then go to Settings. It is heavy on performance, and so should be used with caution.*

**Readiness Checker:** This functional role allows access to the client diagnostic overview panel, in order to keep track of diagnostic tests which have been run. *Note: This role would typically be assigned to the local systems administrator. The URL which tracks diagnostic tests is: /taoClientDiagnostic/Diagnostic/index. A compatibility checker is available under /taoClientDiagnostic/CompatibilityChecker/index.*

**Lock Manager:** This additional role allows the removal of locks when the Workspaces extension is installed.


## Authoring Roles:

**Item Author:** This functional role allows the authoring and management of items and [Media](../media/media-manager.md).

**Test Author:** This additional role allows the authoring and management of tests. *Note: It needs to be used in combination with the Item Author role to be able to select items and assemble tests.*

## Roles for Conducting Assessments:

**Test Center Administrator:** This functional role can manage [Proctors](../appendix/glossary.md#proctor) (create, remove, authorize) and can also [proctor](../test-center/proctoring.md) a delivery.

**Proctor Administrator:** This functional role allows the instant proctoring of deliveries associated with a [Test Center](../appendix/glossary.md#test-center), without pre-authorization by a Test Center Administrator. *Note: The only difference to the role of proctor is that pre-authorization is not necessary. This role is only managed by the test center Administrator if the latter has been assigned as a proctor.*

**Proctor:** This functional role allows the proctoring of test deliveries associated with a specific Test Center. *Note: A proctor must be authorized by a Test Center Administrator before being able to proctor a test.*

**Reviewer:** This functional role is for reviewing test [Results](../appendix/glossary.md#results). It grants access to the Results panel only.

## Test-taking Role:

**Test-taker:** This functional role allows a [Test-taker](../appendix/glossary.md#test-taker) to take a test, if eligible by Test Center association.

## Technical Roles:

**REST Publisher:** This technical role allows use of the Publishing API, for system-to-system publication processes.

**Task Queue Manager:** This technical role allows for the management of the task queue.

See the section on [User Management](../administrative-features/user-management.md) for information on how roles and permissions are assigned.


