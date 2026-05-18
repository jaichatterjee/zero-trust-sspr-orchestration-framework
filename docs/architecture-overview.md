# Architecture Overview

## High-Level Architecture

```text
User
    ↓
Desktop Shortcut (SCCM)
    ↓
Power Automate UI
    ↓
Identity & Device Validation
    ↓
Risk Evaluation
    ↓
Decision Engine
    ↓
Recovery Action / Escalation
```

---

## Major Components

### Identity Layer
- Entra ID
- SSPR API
- Conditional Access

### Device Layer
- Intune
- Compliance validation

### Security Layer
- Sentinel
- Behavioral signals

### ITSM Layer
- ServiceNow
- Manual verification workflows
