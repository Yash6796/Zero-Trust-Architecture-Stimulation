# 🎯 Conditional Access Policy Scenarios

This file outlines common Conditional Access (CA) policies based on Zero Trust principles.

## 🛑 Block Access from Risky Users

```yaml
Condition:
  Sign-in Risk: High
Control:
  Block Access
🔐 Require MFA for Admins
Condition:
  Role: Global Administrator
Control:
  Require Multi-Factor Authentication (MFA)
📵 Block Access from Personal Devices
Condition:
  Device is not compliant
Control:
  Block Access
📍 Require Location-Based Policies
Condition:
  Sign-in from outside India
Control:
  Require MFA
