# Access Control Models – DAC, MAC, RBAC, ABAC

Access control determines who can access what resources in a system. It's a fundamental aspect of cybersecurity and is implemented through various models.

## 1. DAC – Discretionary Access Control

In DAC, the owner of the resource determines who has access. It is commonly used in personal operating systems like Windows and Linux.

### Pros:
- Flexible and easy to implement

### Cons:
- Less secure due to user-based permissions

## 2. MAC – Mandatory Access Control

Access decisions are enforced by a central authority based on classification levels. It’s commonly used in military or government systems.

### Pros:
- Highly secure and strict

### Cons:
- Complex and less flexible

## 3. RBAC – Role-Based Access Control

Access is granted based on the user’s role within an organization. Roles are assigned permissions, and users are assigned to roles.

### Pros:
- Scalable and easy to manage in organizations

### Cons:
- Role explosion in complex environments

## 4. ABAC – Attribute-Based Access Control

Access is granted based on a combination of attributes (user, resource, environment).

### Examples of attributes:
- Time of access
- User’s department
- Device used

### Pros:
- Dynamic and fine-grained control

### Cons:
- Complex policy management

## Summary Description:

- **DAC (Discretionary Access Control):** Based on resource ownership. Commonly used in personal computers.
- **MAC (Mandatory Access Control):** Based on predefined security clearance levels. Used in military systems.
- **RBAC (Role-Based Access Control):** Based on roles within an organization. Suitable for corporate environments.
- **ABAC (Attribute-Based Access Control):** Based on various user and context attributes. Ideal for cloud and modern applications.

## Conclusion

Each access control model offers different benefits depending on the environment and security requirements. Understanding and applying them appropriately is essential for effective access management.