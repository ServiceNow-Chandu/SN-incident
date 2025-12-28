# Architecture Overview

## Tables
- incident (OOB)
- u_assignment_matrix
- u_oncall_rota

## Logic Flow
1. Incident created
2. Priority calculated via Script Include
3. Auto-assignment executed asynchronously
4. SLAs attached
5. Notifications triggered
6. Metrics collected via PA

## Design Principles
- Separation of logic
- Reusability
- Minimal customization to OOB tables
