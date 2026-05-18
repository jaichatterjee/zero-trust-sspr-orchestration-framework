# Recovery Workflow

```text
User Request
      ↓
Device Validation
      ↓
Identity Validation
      ↓
Behavior Evaluation
      ↓
Risk Calculation
      ↓

Low Risk?
├── Yes → Allow SSPR
│
└── No
      ↓

Medium Risk?
├── Yes → MFA Enforcement
│
└── No
      ↓

High Risk?
├── Strong Identity Proofing
│
└── Critical
      ↓

Block Access
↓
ServiceNow Escalation
```
