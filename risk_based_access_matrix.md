
---

### 📁 `risk_based_access_matrix.md`

```markdown
# 📊 Risk-Based Access Control Matrix (Simulation)

This matrix simulates how risk levels determine access decisions in a Zero Trust model.

| User Risk Level | Device Risk Level | Access Action           | Policy Triggered                    |
|------------------|--------------------|--------------------------|-------------------------------------|
| Low              | Low                | Allow Access             | Standard Sign-in                    |
| Medium           | Low                | Require MFA              | Identity Risk Detected              |
| High             | Low                | Block Access             | Compromised Identity                |
| Low              | Medium             | Require Device Compliant | Defender Risk Score Medium          |
| Low              | High               | Block Access             | Defender Risk Score High            |
| High             | High               | Block + Alert Admin      | Emergency Incident                  |

## ✅ Example Use Cases

- A user logs in from an infected personal laptop → Blocked.
- Admin tries to activate PIM role from unknown IP → MFA required.
- Normal employee accesses Teams from compliant laptop → Allowed.

## 📷 Suggested Visual

Consider creating a PNG table image version of this matrix using Canva or Excel for added visual clarity.

