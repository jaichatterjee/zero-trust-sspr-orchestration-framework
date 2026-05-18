# Orchestration Model

## Purpose

The orchestration layer coordinates recovery workflows while separating workflow execution from security decision-making.

Important principle:

Power Automate coordinates workflow execution only and does not determine trust decisions.

---

## Responsibilities

### User Entry Layer

Provides:

- Password Reset
- Forgotten Password
- MFA Reset
- Cannot Access Account

---

### Workflow Coordination

Responsible for:

- Input collection
- Flow routing
- ITSM integration
- Status tracking

---

### Trust Evaluation Boundary

Trust evaluation remains external and is delegated to:

- Entra ID risk scoring
- Intune compliance
- Conditional Access
- Sentinel signals

---

## Execution Flow

```text
User Request
      ↓
Power Automate
      ↓
Collect Inputs
      ↓
Call Trust Sources
      ↓
Receive Decision
      ↓
Execute Action
```
