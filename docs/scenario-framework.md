# Scenario Framework

| Scenario | Risk | Control | Automation |
|---|---:|---|---|
| Pre-expiry reset | Low | MFA | Full |
| Expired password | Medium | Two factors | Full |
| Forgot password (active session) | Medium+ | Device + MFA | Conditional |
| Locked out | High | Strong identity proofing | Controlled |
| Device lost | High | Device wipe | Semi |
| Device lost + no access | Critical | Manual verification | None |
| MFA failure | Attack | Block and investigate | None |

---

## Purpose

The framework maps common recovery events to risk-based actions.
