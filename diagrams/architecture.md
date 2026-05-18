# Architecture Diagram

```text
          Zero Trust SSPR Orchestration Framework
                          │
                          ↓
 ┌─────────────────────────────────────────────────────────┐
 │                  Identity Layer                         │
 │                                                         │
 │  Entra ID | SSPR API | Conditional Access | Risk        │
 └─────────────────────────────────────────────────────────┘
                          ↓
 ┌─────────────────────────────────────────────────────────┐
 │                  Device Trust Layer                     │
 │                                                         │
 │  Intune | Compliance Validation | Device Binding        │
 └─────────────────────────────────────────────────────────┘
                          ↓
 ┌─────────────────────────────────────────────────────────┐
 │                Orchestration Layer                      │
 │                                                         │
 │  Power Automate | Flow Logic | UI | Routing             │
 └─────────────────────────────────────────────────────────┘
                          ↓
 ┌─────────────────────────────────────────────────────────┐
 │               Security & Telemetry                      │
 │                                                         │
 │  Sentinel | Behavioral Analytics | Risk Signals         │
 └─────────────────────────────────────────────────────────┘
                          ↓
 ┌─────────────────────────────────────────────────────────┐
 │                 Recovery / ITSM Layer                   │
 │                                                         │
 │  ServiceNow | Verification | Escalation                 │
 └─────────────────────────────────────────────────────────┘
```
