# 🛠️ Simulated Incident Response Using Microsoft Defender

## 🎯 Incident

Device infected with malware, attempting to access SharePoint and OneDrive.

## 🧩 Tools Used

- **Defender for Endpoint** — Detects risky device behavior.
- **Defender for Cloud** — Flags non-compliant device posture.
- **Conditional Access** — Blocks access from high-risk devices.
- **Microsoft Entra ID** — Identity verification, MFA enforcement.

## 🚦 Response Flow

1. Defender flags device as **"High Risk"** due to malware.
2. Conditional Access policy blocks access to corporate resources.
3. Entra logs alert in sign-in risk report.
4. Admin notified for remediation.

## 🧪 Simulated Screenshot Suggestions

- Mock dashboard showing “High risk device”.
- Conditional Access denial message.
- Defender alert with “malware activity” on endpoint.

## 📝 Lessons Simulated

- Device risk integration with identity
- Real-time risk-based access decisions
- Unified incident detection and action

