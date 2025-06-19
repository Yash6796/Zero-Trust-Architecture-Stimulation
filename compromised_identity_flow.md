# 🚨 Simulated Flow: Compromised Identity Attack

## 🎯 Scenario

An attacker gains access to a user’s credentials via phishing and signs in from an unusual location.

## 🔄 Attack Flow (Simulated)

1. **UserA** receives a phishing email and enters credentials on a fake login page.
2. Attacker logs in from an IP in Nigeria.
3. Microsoft Entra ID detects **High-Risk Sign-In**.
4. Conditional Access policy **blocks access** immediately.
5. Admin receives alert from **Defender for Identity**.
6. Incident is marked for investigation.

## 🛡️ Response Simulation

| Tool                   | Action Taken                          |
|------------------------|----------------------------------------|
| Entra ID               | Risky sign-in blocked                  |
| Conditional Access     | Session denied                         |
| Defender for Identity  | Alert created: "Unusual sign-in"       |
| Admin Action           | Account reset, review audit logs       |

## 📝 Notes

- This scenario helps simulate a real-world compromise.
- Mock screenshots can be added for Entra sign-in logs and alerts.

