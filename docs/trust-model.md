# Progressive Trust Model

## Purpose

The framework applies progressive trust validation where access decisions are based on multiple layers rather than a single authentication signal.

---

## Trust Layers

### Layer 1 — Device Trust

Purpose:

- Validate managed device state
- Confirm compliance

Controls:

- Intune compliance
- Device binding

---

### Layer 2 — Identity Validation

Purpose:

- Validate user identity

Controls:

- MFA
- Authentication verification

---

### Layer 3 — Behavioral Validation

Purpose:

- Identify abnormal behavior

Signals:

- Impossible travel
- Location anomalies
- Usage deviation

---

### Layer 4 — Risk Evaluation

Purpose:

- Combine security signals

Inputs:

- Identity risk
- Device trust
- Behavioral data

---

### Layer 5 — Action

Possible outcomes:

- Allow
- Step-up verification
- Block
- Escalate
