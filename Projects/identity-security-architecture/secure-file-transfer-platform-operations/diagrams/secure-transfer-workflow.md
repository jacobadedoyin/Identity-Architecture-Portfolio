# Secure Transfer Workflow

## Purpose

This workflow shows a high-level secure file transfer process for MOVEit Secure Transfer.

It demonstrates how access requirements, secure folder structure, permissions, user support, and transfer operations can be managed in a controlled way.

## Workflow

```mermaid
flowchart TD
    A[Secure Transfer Requirement Identified] --> B[Confirm User or Stakeholder Need]
    B --> C[Identify or Create Transfer Area]
    C --> D[Apply Folder Hierarchy]
    D --> E[Assign Permissions]
    E --> F[Grant or Update User Access]
    F --> G[Provide User Guidance or Training]
    G --> H[Support Secure Transfer Activity]
    H --> I[Review Access Requirement]
    I --> J{Still Required?}
    J -->|Yes| K[Retain or Amend Access]
    J -->|No| L[Remove Access and Close Out]
```
