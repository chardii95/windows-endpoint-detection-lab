# 🔍 Account Compromise Investigation

## 🧠 Summary
Multiple failed login attempts were observed followed by the creation of a new user account and assignment of administrative privileges.

## 🧾 Evidence
- Event ID 4625: Failed login attempts
- Event ID 4720: User account created
- Event ID 4728/4732: User added to Administrators group

## ⏱ Timeline
- Failed login attempts detected
- Successful login observed
- User account "attacker" created
- User added to Administrators group

## 🚨 Severity
High

## ⚠️ Justification
The creation of a new administrative account indicates potential compromise and persistence. This gives an attacker full control over the system.

## 🛠 Recommended Actions
- Disable the suspicious account
- Reset credentials
- Review logs for further activity
- Investigate source of initial access
