# Analytics Platform JML Workflow

## Purpose

This workflow shows the joiner, mover, and leaver process used to manage access across data analytics platforms such as Qlik and Tableau.

The aim is to make user access administration consistent, repeatable, and easier to evidence without exposing confidential platform or user information.

## Workflow Overview

```mermaid
flowchart TD
    A[Access Request Received] --> B[Identify Request Type]

    B --> C{JML Type}

    C -->|Joiner| D[Create or Enable Platform Access]
    C -->|Mover| E[Review Existing Access]
    C -->|Leaver| F[Remove Platform Access]

    D --> G[Assign Appropriate Access Level]
    E --> H[Update Access Based on New Requirement]
    F --> I[Recover Licence / Remove User]

    G --> J[Update Licence Tracker]
    H --> J
    I --> J

    J --> K[Confirm Completion]
    K --> L[Record Evidence / Update Support Notes]
```
