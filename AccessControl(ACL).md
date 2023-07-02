# ACL

- **RBAC** is a way to control who can access what in a computer system. Instead of giving permissions directly to individuals, permissions are assigned to roles. Users are then assigned roles, and their access rights are determined by the roles they have. It improves security, simplifies management, helps with compliance, and makes things more efficient.

- **Role/Permission Hierarchy Example:**

        Role: Administrator
        Permissions: Full access to all system resources, user management, configuration changes.

        Role: Manager
        Permissions: Access to specific department resources, team management.

        Role: Supervisor
        Permissions: Access to team-specific resources, task assignment.

        Role: Employee
        Permissions: Access to personal work files, task completion.

        Role: Guest
        Permissions: Limited access to public information, no editing or administrative privileges.
  
- **The approach to implement RBAC involves the following steps:**

     1. Identify roles.
     2. Define permissions.
     3. Assign permissions to roles.
     4. Assign roles to users.
     5. Review and refine.
     6. Training and communication.
     7. Regular audits.
 
- **Authenticate = Verifies the identity of a user or process. Authorize = Determines if the user / system has permission to use a resource or carry out an action**

- **The three primary rules defined for RBAC (Role-Based Access Control) are:**

  - Role Assignment: A user can exercise permissions only if they have been assigned or selected a specific role.

  - Role Authorization: The active role of a user must be authorized for that user. Users can only take on roles for which they are 
        authorized.

  - Permission Authorization: A user can exercise a permission only if that permission is authorized for their active role. Users can 
        only use permissions that they are specifically authorized to use based on their role.


- **RBAC helps maintain security and control by ensuring that people only have access to what they need for their job. It simplifies the process of managing access and reduces the risk of unauthorized access or mistakes in granting permissions.**

- **Access rights in RBAC are associated with roles. Users are assigned to specific roles, and the access rights are defined at the role level. Authorization is activated after a user successfully authenticates. RBAC benefits a business by improving security, simplifying access management, ensuring compliance, and offering scalability and flexibility.**
