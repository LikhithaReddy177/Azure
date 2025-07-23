# Resource Creation Hierarchy

## I. Management Group

In Microsoft Azure, a **management group** is used to organize and manage access, policies, and compliance across multiple Azure subscriptions. It provides a level of scope above subscriptions, allowing for consistent governance controls.

- **Hierarchy Support**:  
  Management groups can contain child management groups and subscriptions, forming a tree structure.
  
- **Purpose**:
  - Apply policies at scale.
  - Organize large environments.
  - Centralize compliance and access management.

---

## II. Subscription

A **subscription** in Azure is a logical container used for managing resources, access, and billing.

### Key Features:

- **Resource Management**:
  - Organizes Azure resources like VMs, storage, databases.
  - Resources within a subscription share policies and settings.

- **Billing**:
  - Each subscription has a unique billing account.
  - Tracks usage and costs.

- **Access Control**:
  - Uses **Role-Based Access Control (RBAC)** for managing user access.

---

# III. Azure Resource Group

A **Resource Group** is a logical container that holds related Azure resources like VMs, storage accounts, web apps, etc.

### Benefits:
- Organized resource management.
- Lifecycle management of grouped resources.
- Easier access control and monitoring.


# IV .Azure Resources :


An **Azure Resource** is any manageable item available in Azure. This includes services or components that you can create, configure, and manage within your Azure subscription.

### 🔹 Examples of Azure Resources:
- Virtual Machines (VMs)
- Storage Accounts
- SQL Databases
- Virtual Networks
- Web Apps
- Key Vaults
- Azure Functions
- Azure Kubernetes Service (AKS)

---

## Characteristics of Azure Resources:

- **Resource ID**: Each resource has a unique ID.
- **Resource Type**: Defines the kind of service (e.g., `Microsoft.Storage/storageAccounts`).
- **Resource Group**: Every resource belongs to one resource group.
- **Region**: Resources are deployed in specific Azure regions.
- **Tags**: Key-value pairs used for organizing and managing resources (e.g., by department or environment).
- **Lifecycle**: Resources can be created, updated, deleted, or moved.


